<template>
  <section class="mt-0 mt-lg-5">
    <div class="container-fluid p-0">
      <div class="row" v-for="(list, index) in lists" :key="index" :id="list.title">
        <div class="col-lg-6 p-0" :class="[{'order-1 order-lg-0': index % 2 === 0}]">
          <div class="wrapper position-relative image-overlay">
            <figure className="m-0">
              <img class="img-fluid w-100 h-image-100vh" :src="list.image" :alt="list.name" />
            </figure>
            <div class="position-absolute top-50 start-50 translate-middle p-4 text-white z-999 text-center w-100">
              <h2 class="display-2 mp-0 fw-bolder">{{list.title}}</h2>
              <p class="mp-0">{{list.description}}</p>
            </div>
          </div>
        </div>
        <div class="col-lg-6 p-0" :class="[{'order-0 order-lg-1': index % 2 === 0}]">
          <div class="row">
            <div class="col-6 p-0" v-for="(child, index) in list.childImages" :key="index">
              <img class="img-fluid w-100 h-image-50vh" :src="child.image" :alt="child.name" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ContentComponent",
  data() {
    return {
      lists: [
        {
          image: require("@/assets/source/image/img-1.jpg"),
          name: "image-1",
          title: "Nature",
          description: "Lorem ipsum dolor sit amet.",
          childImages: [
            {
              image: require("@/assets/source/image/img-2.jpg"),
              name: "image-2",
            },
            {
              image: require("@/assets/source/image/img-3.jpg"),
              name: "image-3",
            },
            {
              image: require("@/assets/source/image/img-4.jpg"),
              name: "image-4",
            },
            {
              image: require("@/assets/source/image/img-5.jpg"),
              name: "image-5",
            },
          ],
        },
        {
          image: require("@/assets/source/image/img-6.jpg"),
          name: "image-6",
          title: "Tatami",
          description: "Lorem ipsum dolor sit amet.",
          childImages: [
            {
              image: require("@/assets/source/image/img-7.jpg"),
              name: "image-7",
            },
            {
              image: require("@/assets/source/image/img-8.jpg"),
              name: "image-8",
            },
            {
              image: require("@/assets/source/image/img-9.jpg"),
              name: "image-9",
            },
            {
              image: require("@/assets/source/image/img-10.jpg"),
              name: "image-10",
            },
          ],
        },
        {
          image: require("@/assets/source/image/img-11.jpg"),
          name: "image-11",
          title: "Quil",
          description: "Lorem ipsum dolor sit amet.",
          childImages: [
            {
              image: require("@/assets/source/image/img-12.jpg"),
              name: "image-12",
            },
            {
              image: require("@/assets/source/image/img-13.jpg"),
              name: "image-13",
            },
            {
              image: require("@/assets/source/image/img-14.jpg"),
              name: "image-14",
            },
            {
              image: require("@/assets/source/image/img-15.jpg"),
              name: "image-15",
            },
          ],
        },
      ]
    }
  }
}
</script>
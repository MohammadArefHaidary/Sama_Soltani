<script>
export default {
  data: () => {
    return {
      relatedProject: {
        relatedProjectsHeading: "Related Projects",
        relatedProjects: [
          {
            id: 1,
            title: "Mobileadfh UI",
            img: require("@/static/images/92362e_94aad63670a8daad273fa2b576717ea1.jpg"),
          },
          {
            id: 2,
            title: "Web Application",
            img: require("@/static/images/92362e_94aad63670a8daad273fa2b576717ea1.jpg"),
          },
          {
            id: 3,
            title: "UI Design",
            img: require("@/static/images/92362e_cbccd557b80628c714b0dd7c1d2cc9c5.jpg"),
          },
          {
            id: 4,
            title: "Kabul Mobile App UI",
            img: require("@/static/images/92362e_e5aad61348614df447d3243a6d4dc571.jpg"),
          },
        ],
      },
    };
  },
};
</script>

<template>
  <div
    class="
      mt-10
      pt-10
      sm:pt-14 sm:mt-20
      border-t-2 border-primary-light
      dark:border-secondary-dark
    "
  >
    <p
      class="
        font-general-regular
        text-primary-dark
        dark:text-primary-light
        text-3xl
        font-bold
        mb-10
        sm:mb-14
        text-left
      "
    >
      {{ relatedProject.relatedProjectsHeading }}
    </p>

    <div class="grid grid-cols-1 sm:grid-cols-4 gap-10">
      <div v-for="item in relatedProject.relatedProjects" :key="item.id">
        <img
          :src="item.img"
          class="rounded-xl cursor-pointer"
          :alt="item.title"
        />
      </div>
    </div>
  </div>
</template>

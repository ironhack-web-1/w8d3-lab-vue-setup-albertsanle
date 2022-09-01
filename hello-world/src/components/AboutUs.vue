<template>
  <div>
    <h1>My first Vue project</h1>
    <p>{{ aboutMe }}</p>
  </div>
</template>
<script>
export default {
  data() {
    return {
      aboutMe:
        "Lorem ipsum dolor sit amet consectetur, adipiscing elit conubia dignissim morbi, dis fusce volutpat velit. Nunc cubilia quis iaculis diam tempor sed morbi sociosqu malesuada facilisi, aenean auctor mus habitasse etiam leo magnis ridiculus. Tempor eu conubia nunc lectus et lacus vestibulum congue quisque nisi, aliquet nascetur litora tempus ullamcorper magnis iaculis nulla imperdiet hac, natoque ut maecenas accumsan dictum commodo urna lacinia fusce.",
    };
  },
};
</script>

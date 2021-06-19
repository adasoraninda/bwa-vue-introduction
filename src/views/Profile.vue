<template>
  <div class="profile">
    <h1>This is an profile page</h1>
    <div class="contaier">
      <div class="row justify-content-center">
        <div class="col-lg-6">
          <div class="media text-left">
            <img
              src="https://avatars.githubusercontent.com/u/60052302?s=60&v=4"
              alt="profile-photo"
              class="user-pic mr-3"
            />
            <div class="media-body">
              <h5 class="mt-0">{{ firstName }} {{ lastName }}</h5>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Dolorum, consectetur placeat fugiat sapiente quidem dolorem
                dolor libero harum iusto. Explicabo porro autem molestiae, ipsum
                totam dolore architecto a esse nam?
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "profile",
  data: function () {
    return {
      firstName: "Adadua karunia",
      lastNama: "putera",
    };
  },
};
</script>

<style scoped>
.user-pic {
  border-radius: 200%;
  height: 80px;
  width: 80px;
}
</style>
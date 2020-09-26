<template>
  <div class="container is-fluid">
    <div class="block"></div>
    <div class="columns is-centered">
      <figure class="image is-128x128">
        <img
          class="is-rounded"
          src="https://www.telegraph.co.uk/content/dam/Author%20photos/Adam_WIlliams-small.png"
          alt=""
        />
      </figure>
    </div>
    <div class="block"></div>
    <div class="columns is-centered">
      <h1 class="name">Jackson Morris</h1>
    </div>
    <div class="columns is-centered is-multiline">
      <div class="column is-narrow">
        <div class="card">
          <div class="card-content has-text-centered">
            <div class="is-flex is-horizontal-center">
              <figure class="row image is-128x128">
                <img
                  class="is-rounded"
                  src="https://www.kt-webtasarim.com/uploads/hizmetler/logo_designing_category_icon_1.png"
                />
              </figure>
            </div>
            <h1 class="card-title">Logo Design</h1>
            <br />
            <p class="card-description">Lorem ipsum dolor sit amet.</p>
          </div>
        </div>
      </div>
      <div class="column is-narrow">
        <div class="card">
          <div class="card-content has-text-centered">
            <div class="is-flex is-horizontal-center">
              <figure class="row image is-128x128">
                <img
                  class="is-rounded"
                  src="https://icons.iconarchive.com/icons/graphicloads/colorful-long-shadow/256/Bed-icon.png"
                />
              </figure>
            </div>
            <h1 class="card-title">Interior Architectural Design</h1>
            <br />
            <p class="card-description">Lorem ipsum dolor sit amet.</p>
          </div>
        </div>
      </div>
      <div class="column is-narrow">
        <div class="card">
          <div class="card-content has-text-centered">
            <div class="is-flex is-horizontal-center">
              <figure class="row image is-128x128">
                <img
                  class="is-rounded"
                  src="https://image.flaticon.com/icons/png/512/1454/1454773.png"
                />
              </figure>
            </div>
            <h1 class="card-title">3D Modeling</h1>
            <br />
            <p class="card-description">Lorem ipsum dolor sit amet.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style lang="scss" scoped>
.card {
  background-color: #7649fc;
  radius: "75";
}
.card-title {
  color: white;
  font-size: 1.5em;
}
.card-description {
  color: white;
  font-size: 0.9em;
}
.is-horizontal-center {
  justify-content: center;
}
.name {
  font-weight: bold;
  font-size: 2em;
}
</style>
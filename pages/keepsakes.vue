<template>
  <div class="container">
    <div class="section links">
      <Nav />
    </div>
    <div class="section tribute">
      <!-- CONTENT START -->
      <h1 class="title">Keepsakes</h1>
      <h2 class="highlight">If you would like a memorial hoodie, please fill out the form below.</h2>
      <div class="form-wrapper">
        <iframe
          src="https://tally.so/r/mZbdaa?transparentBackground=1&formEventsForwarding=1"
          width="100%"
          height="600"
          frameborder="0"
          marginheight="0"
          marginwidth="0"
          title="In Loving Memory of Shaun Riley: Memorial Sweater Order Form"
          style="border:0; position:relative;"
        ></iframe>
      </div>
      <!-- CONTENT END -->
    </div>
  </div>
</template>

<script>
export default {
  head: {
    title: 'In Loving Memory of Shaun Riley: Memorial Sweater Order Form',
    meta: [
      { name: 'viewport', content: 'width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0' }
    ],
    script: [
      { src: 'https://tally.so/widgets/embed.js', async: true }
    ]
  }
}
</script>

<style lang="scss">
h2 {
  color: white
}
.form-wrapper {
  width: 90%;
  min-height: 600px;
  position: relative;
}
</style>
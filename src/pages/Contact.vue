<template>
  <Layout>
    <div class="container">
      <div class="contact-header">
        <h1 class="contact-title">About</h1>
        <div class="profile">
          <div class="profile-img">
            <img
              class="g-image g-image--lazy g-image--loaded"
              src="https://github.com/sgartgallery/gallery/raw/master/uploads/img-20190727-wa0000-2.jpeg"
              sizes="(max-width: 100%) 100vw, 1272px"
            />
          </div>
          <div class="profile-text">
            <p>
              Shushma Gupta makes paintings, drawings and mixed media artworks.
              By applying abstraction, Shushma tries to develop forms that do
              not follow logical criteria, but are based only on subjective
              associations and formal parallels, which incite the viewer to make
              new personal associations.
            </p>
            <p>
              Her works reference nature, spirituality, and inspirations from 
              everyday life. Shushma currently lives and works in Mumbai.
            </p>
            <p>
              If you have an upcoming or interesting project you'd like to
              discuss, get in touch at
              <a href="mailto: guptashushma@gmail.com">guptashushma@gmail.com</a>.
            </p>
          </div>
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {};
</script>

<style scoped>
.contact-header {
  padding: 2rem 0 4rem 0;
}
.contact-title {
  font-size: 4rem;
  margin: 0 0 4rem 0;
  padding: 0;
}
.profile {
  display: flex;
}

.profile-img {
  flex: 1 1 50%;
  padding: 5px;
}
.profile-text {
  flex: 1 1 50%;
  padding: 5px;
}

@media (max-width: 700px) {
  .profile {
    display: flex;
    flex-direction: column;
  }

  .profile-img {
    flex: 1 1 100%;
    padding: 5px;
  }
  .profile-text {
    flex: 1 1 100%;
    padding: 5px;
  }
}

.sender-info {
  display: flex;
  flex-wrap: wrap;
  margin-bottom: 2rem;
}
.sender-info > div {
  flex: 1;
  margin-right: 4rem;
}
.sender-info > div:last-of-type {
  margin: 0;
}
input:focus,
textarea:focus {
  border-color: var(--color-contrast-1);
}
input,
textarea {
  background: transparent;
  border: 1px solid var(--color-base-1);
  outline: none;
  border-radius: 0.3rem;
  padding: 0.8rem 1rem;
  color: inherit;
  font-size: 1rem;
  width: 100%;
}
textarea {
  resize: none;
  height: 140px;
}
.button {
  color: var(--color-base);
  background: var(--color-contrast);
  outline: none;
  border: 0;
  font-size: 0.8rem;
  padding: 0.8rem 1.6rem;
  border-radius: 0.3rem;
  margin-top: 2rem;
  cursor: pointer;
  transition: opacity 0.25s ease;
  font-size: 500;
  letter-spacing: 0.035em;
}
.button:hover {
  opacity: 0.6;
}
.button:focus {
  border: 1px solid var(--color-base-1);
}
</style>

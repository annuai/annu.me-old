<template>
  <Layout>
    <div class="container">

      <div class="resume-header">
        <h1 class="resume-title">Say hi!</h1>
        <p>Im an Industrial Designer currently doing undergraduation</p>
      </div>
      <div>See my resume <a href="/resume.pdf" target="_blank" class="resume__link">here</a></div>
      <img 
                        src="../../static/resume.png"
                        alt="Annuai Resume" 
                        class="resume-img"
                    />

    </div>
  </Layout>
</template>

<script>
export default {}
</script>

<style scoped>
.resume-img{
  width:100rem;
  margin:0rem;
}
.contact-header {
  padding: 2rem 0 4rem 0;
}
.contact-title {
  font-size: 4rem;
  margin: 0 0 4rem 0;
  padding: 0;
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
input:focus,textarea:focus {
  border-color: var(--color-contrast-1);
}
input,textarea {
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


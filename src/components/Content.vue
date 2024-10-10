<template>
  <main>
    <div class="container">
      <h1>An awesome title</h1>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. <span>Fuga error</span> quasi
        pariatur, dolorem blanditiis nostrum enim nisi architecto ratione ea, totam consequuntur
        explicabo delectus asperiores tempora autem tenetur numquam perspiciatis! Corporis doloribus
        laboriosam inventore placeat consequuntur recusandae repudiandae corrupti ex eos quibusdam
        quaerat saepe magnam culpa sunt, dolorum atque aut debitis, fugiat excepturi et
        exercitationem obcaecati porro maiores! Dolorem, maxime. Quisquam ut voluptates hic
        perspiciatis autem quasi quis. Officiis quas corrupti <span>officia</span> in eos beatae.
        Modi atque dolore reiciendis id tenetur, explicabo distinctio, porro quo similique, nihil at
        cumque officia. Quos inventore, commodi, nobis, fugiat eum eveniet fugit asperiores hic
        ratione tenetur deserunt ex facere quod. Modi, harum consequuntur tenetur temporibus ea quam
        voluptate, veniam aut, ipsa tempora ullam! Cupiditate?
      </p>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Odit explicabo, dignissimos iusto
        vero vitae ullam <span>quidem amet</span> esse voluptas. Distinctio commodi repudiandae,
        deleniti a eveniet dolorem nisi eius sint dolore! Facilis ut labore rerum
        <span>dolorem</span> delectus iusto architecto officia quis cum magnam aliquid mollitia ad
        nam, in, at pariatur vero unde similique nihil ullam sunt provident minima asperiores nulla!
        Voluptatem.
      </p>
    </div>
  </main>
</template>
<style scoped>
main {
  /* border: 2px solid aqua; */
  border-top: 2px solid var(--main-orange);
  border-bottom: 2px solid var(--main-orange);
  height: calc(100vh - var(--header-heigth) - var(--footer-heigth));
  padding-top: 20px;
}

h1 {
  text-decoration: underline var(--main-orange);
  margin-bottom: 20px;
}
p {
  margin-bottom: 20px;
  line-height: 20px;
}
span {
  color: var(--main-orange);
}
</style>

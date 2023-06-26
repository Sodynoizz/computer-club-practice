<svelte:head>
  <style>
    body {
      background: pink;
      padding: 40px;
    }
  </style>
</svelte:head>

<div id="all-context">
  <h1>Cat Photo App</h1>
  <section>
    <h2>Cat Photo</h2>
    <p>
      See more <a href="https://unsplash.com/images/animals/cat">cat</a> photo in
      our gallery
    </p>
    <div id="cat-meme">
      <img
        src="https://images.wallpaperscraft.com/image/single/cat_surprise_look_96597_3840x2160.jpg"
        alt="This is a cat"
      />
    </div>
  </section>

  <section>
    <div>
      <h3>Things cat likes</h3>
      <ul>
        <li>Cat nip</li>
        <li>Laser point</li>
        <li>Lasana</li>
      </ul>
      <figure>
        <img
          src="https://cdn.pixabay.com/photo/2014/11/30/14/11/cat-551554_640.jpg"
          alt="This is a CAT"
        />
        <figcation><br />This <em>is</em> a <strong>cat</strong>.</figcation>
      </figure>
    </div>
  </section>
</div>

<style>
  #cat-meme img{
    width: 300px;
  }

  #all-context {
    background-color: #FEFBBD;
    padding: 40px;
  }
</style>

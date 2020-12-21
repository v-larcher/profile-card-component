<script>
</script>

<style>
  .card {
    position: fixed;
    box-shadow: 0 35px 40px 20px rgba(25, 130, 155, 0.4),
      0 50px 40px 40px rgba(25, 130, 155, 0.1);
    background-color: white;
    transition: 0.3s;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    display: block;
    border-radius: 15px;
  }

  .header-background {
    position: static;
    display: block;
    margin: auto;
    z-index: 1;
    border-radius: 15px 15px 0px 0px;
  }

  .avatar {
    position: relative;
    display: block;
    margin: auto;
    margin-top: -15%;
    border-radius: 75%;
    border: 5px solid white;
    z-index: 2;
  }

  .container {
    padding: 2px 16px;
  }

  .line {
    position: -webkit-sticky;
    margin-top: 25px;
    margin-bottom: 10px;
    border-top: 0.1px;
    color: #ddd;
    width: 109%;
    margin-left: -15px;
  }

  .core {
    text-align: center;
  }

  .city {
    margin-top: -10px;
    font-size: 14px;
    color: #777;
  }

  .unity {
    margin-top: -18px;
    margin-bottom: 20px;
    font-size: 10.6px;
    color: #777;
    letter-spacing: 0.12em;
  }

  .age {
    color: #777;
    display: inline-block;
    margin-left: 5px;
  }

  .name {
    display: inline-block;
  }

  .row {
    display: flex;
    text-align: center;
  }

  .column {
    flex: 50%;
  }
</style>

<div class="card">
  <img class="header-background" src="/assets/bg-pattern-card.svg" alt="" />
  <img class="avatar" src="/assets/image-victor.jpg" alt="Avatar" />
  <div class="container">
    <div class="core">
      <strong class="name">Victor Crest</strong>
      <p class="age">26</p>
      <p class="city">London</p>
    </div>
    <hr class="line" />
    <div class="row">
      <div class="column">
        <h4><b>80K</b></h4>
        <p class="unity">Followers</p>
      </div>
      <div class="column">
        <h4><b>803K</b></h4>
        <p class="unity">Likes</p>
      </div>
      <div class="column">
        <h4><b>1.4K</b></h4>
        <p class="unity">Photos</p>
      </div>
    </div>
  </div>
</div>

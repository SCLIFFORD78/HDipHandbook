<script>
  import { title, subTitle, navBar, welcomeBar } from "../stores";
  import hive from "../assets/beehive.jpg";
  import background from "../assets/background.png";
  import selfie from "../assets/selfie.jpeg";
  import collage from "../assets/handbookBackground.jpg";

  title.set("Hive Tracker");
  subTitle.set("Hive Tracker Application");

  navBar.set({
    bar: welcomeBar,
  });
</script>

<div class="uk-width-1-1@m">
  <div class="uk-card uk-card-default uk-card-body ">
    <h1 class="uk-heading-small">Hive Tracker</h1>
    <p class="uk-text-large">
      Beehive monitoring solution using android and web application
      <a class="uk-link-muted" href="https://drive.google.com/file/d/1lWqRwKydCxhq4bCUGJY6P8DB6nIXv4qc/view?usp=sharing">Link</a>
    </p>
  </div>
</div>

<div
  class="uk-background-cover uk-flex-middle uk-padding"
  style="background-image: url({background})"
  uk-grid
>
  

  <div class="uk-width-2-3@m ">
    <div class="uk-card uk-card-default uk-card-body uk-text-emphasis">
      <p>
        A web application in conjunction with an android app and datalogger
        which utilizes Bluetooth BLE technology and cloud storage, to monitor
        temperature and humidity within a beehive. This will allow beekeepers to
        nonintrusively monitor key matrices which indicate overall hive health.
      </p>
      <p>
        Nonintrusive monitoring of conditions within a hive reduces the
        frequency for physical checks which need to be carried out, thus
        reducing the potential stress imposed on the hive, reducing the risk of
        a hive swarming and reduced overall honey yield.
      </p>
      <p>
        Key matrices analysis can also help identify early signs of compromise
        to general hive health.
      </p>
    </div>
  </div>
  
  <div class="uk-width-1-3@m uk-flex-first">
    <div class="uk-card uk-card-default uk-card-body uk-padding-small">
      <!-- svelte-ignore a11y-img-redundant-alt -->
      <img src={selfie} width="1800" height="1200" alt="Image" />
      <p class="uk-text-center uk-text-bold uk-text-large">Sheamus Clifford</p>
    </div>
  </div>
  
</div>
<div class="uk-width-1-1@m uk-flex-first">
  <div class="uk-card uk-card-default uk-card-body uk-padding-small">
    <!-- svelte-ignore a11y-img-redundant-alt -->
    <img src={collage} width="1920px" height="1080px" alt="Image" />
  </div>
</div>

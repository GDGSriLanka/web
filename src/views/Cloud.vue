<template>
  <!DOCTYPE html>
  <html>
    <head>
      <meta charset="utf-8" />
      <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0, shrink-to-fit=no"
      />
      <title>#CloudKasthiram</title>
      <link
        rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.5.2/css/bootstrap.min.css"
      />
    </head>

    <body>
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <img
              class="banner-image"
              :src="
                require('@/assets/img/featureEvent/cropped_kast_header.png')
              "
              align="center"
            />
          </div>
        </div>
        <div class="row">
          <div class="col-md-12">
            <p class="main-title">Hello Developers in Sri Lanka</p>
            <p class="main-subtitle">
              Cloud Kasthiram is a Google Cloud Platform based challenge which
              you can participate and test your cloud knowledge
            </p>
            <br />
          </div>
        </div>

        <div class="row">
          <div class="col-md-12">
            <h3>Why should you be a part of #CloudKasthiram?</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-md-4">
            <img
              style="width: 100%"
              src="https://firebasestorage.googleapis.com/v0/b/gdglkweb.appspot.com/o/Swag%20(1).png?alt=media&token=2736690a-28e1-4f35-9b89-4d415b0fde9c"
            />
          </div>
          <div class="col-md-8">
            <p>
              You get to learn about the Google Cloud Platform and its operation
              from ground up. Then you can test your skills with the Qwiklabs
              platform. You also get <b>1 month free access to Qwiklabs</b> so
              that you can continue to do labs and learn even more...
            </p>
            <p>
              Complete the quests within the given time period and win cool
              rewards.
            </p>
            <p>
              Spread the word by sharing this link:
              gdgsrilanka.org/cloudkasthiram and
              use&nbsp;<strong>#CloudKasthiram</strong>&nbsp;on social media.
              Follow&nbsp;<a href="https://twitter.com/GDGLK">@gdglk</a
              >&nbsp;for all updates!
            </p>
            <p>&nbsp;Let's dance the #CloudKasthiram</p>
          </div>
        </div>
        <div class="row" style="margin-top: 20px">
          <div class="col-md-12">
            <h3>How do I participate?</h3>
            <p>
              In Season 1 you get an opportunity to self study Google Cloud
              Platform starting with one month free access to Qwiklabs and
              receive a cool swag pack upon completion. Sounds interesting?
              Follow the steps below.
            </p>
          </div>
        </div>
        <div class="row">
          <div class="col-md-12">
            <v-stepper v-model="e1">
              <v-stepper-header>
                <v-stepper-step :complete="e1 > 1" step="1">
                  Register
                </v-stepper-step>

                <v-stepper-step :complete="e1 > 2" step="2">
                  Do the labs
                </v-stepper-step>
                <v-stepper-step step="3">
                  Dance the Kasthiram, and claim the swags
                </v-stepper-step>
              </v-stepper-header>

              <v-stepper-items>
                <v-stepper-content step="1">
                  <v-card elevation="0" outlined height="200px">
                    <p>
                      In order to participate in the #CloudKasthiram challenge,
                      you must first register.
                    </p>
                    <p>
                      <button
                        class="btn btn-primary"
                        onClick="location.href='https://docs.google.com/forms/d/e/1FAIpQLScMTQAsKhZljgtZtgFcHeGjHp3-l2qk4Dqi_g_xO9Gwxk1yAA/viewform'"
                        type="button"
                      >
                        REGISTER NOW
                      </button>
                    </p>
                    <br />
                    <p>
                      Want to know how to get one month Qwiklab access? Check
                      out this video
                      <a href="https://youtu.be/R3_A4gFHT2A">tutorial</a>
                    </p>
                     <br />
                  </v-card>
                  <v-divider></v-divider>
                  
                  <v-btn color="success" @click="e1 = 2">
                    I've already Registered
                  </v-btn>
                </v-stepper-content>

                <v-stepper-content step="2">
                  <v-card class="mb-12" outlined elevation="0">
                    <h4>
                      Great.! Now all you have to do, is complete six quests of
                      your choice
                    </h4>
                    <p>Here's a list of Qwiklabs quests which you can do.</p>
                    <h5 class="text-left">Quests</h5>
                    <p class="text-left">
                      <a href="https://google.qwiklabs.com/quests/120"
                        >Getting Started: Create and Manage Cloud Resources</a
                      ><br />
                      <a href="https://www.qwiklabs.com/quests/90"
                        >Understanding Your Google Cloud Costs</a
                      ><br />
                      <a href="https://google.qwiklabs.com/quests/118"
                        >Perform Foundational Infrastructure Tasks in Google
                        Cloud</a
                      ><br />
                      <a href="https://google.qwiklabs.com/quests/121"
                        >Deploy and Manage Cloud Environments with Google
                        Cloud</a
                      ><br />
                      <a href="https://google.qwiklabs.com/quests/128?"
                        >Build and Secure Networks in Google Cloud</a
                      ><br />
                      <a href="https://www.qwiklabs.com/quests/143"
                        >Monitor and Log with Google Cloud Operations Suite</a
                      ><br />
                      <a href="https://google.qwiklabs.com/quests/115"
                        >Build a Website on Google Cloud</a
                      ><br />
                      <a href="https://google.qwiklabs.com/quests/141"
                        >Implement DevOps in Google Cloud</a
                      ><br />
                      <a href="https://google.qwiklabs.com/quests/116?"
                        >Deploy to Kubernetes in Google Cloud</a
                      ><br />
                      <a href="https://google.qwiklabs.com/quests/142?"
                        >Secure Workloads in Google Kubernetes Engine</a
                      ><br />
                      <a href="https://www.qwiklabs.com/quests/32"
                        >Intro to ML: Image Processing</a
                      >
                    </p>
                    <br />
                  </v-card>
                 <v-divider></v-divider>
                  <v-btn color="success" @click="e1 = 3">
                    I did the labs too.!
                  </v-btn>

                  <v-btn @click="e1 = 1" text> Back </v-btn>
                </v-stepper-content>

                <v-stepper-content step="3">
                  <v-card elevation="0" outlined class="mb-12">
                    <h5>
                      Congratulations! You've danced the dance. Now you can
                      claim the reward.
                    </h5>
                    <p>
                      Go to your Qwiklabs profile page, and submit that link to
                      the form below
                    </p>
                    <p>
                      For the completion of the five labs
                      <b>before 8th November 2020</b>, you are eligible for
                    </p>
                    <div class="row">
                      <div class="col-md-4">
                        <img
                          style="width: 80%"
                          src="https://firebasestorage.googleapis.com/v0/b/gdglkweb.appspot.com/o/Swag%20(1).png?alt=media&token=2736690a-28e1-4f35-9b89-4d415b0fde9c"
                        />
                      </div>
                      <div class="col-md-4">
                        <ul>
                          <li>T-Shirt</li>
                          <li>Cap</li>
                          <li>Google sticker card</li>
                        </ul>
                        <button
                          class="btn btn-primary"
                          onClick="location.href='https://docs.google.com/forms/d/e/1FAIpQLSclD0YDV74zzx2YAAJsrFF5o0NBmAGkkUh8pswM93j04xAHkQ/viewform'"
                          type="button"
                        >
                          CLAIM MY REWARD
                        </button>
                      </div>
                    </div>
                  </v-card>
                     <v-divider></v-divider>
                  <v-btn @click="e1 = 2" text> Back </v-btn>
                  <br />
                </v-stepper-content>
              </v-stepper-items>
            </v-stepper>
          </div>
        </div>
      </div>
    </body>
  </html>
</template>
<script>
export default {
  data() {
    return {
      e1: 1,
    };
  },
};
</script>
<style scoped>
p {
  font-size: 16px;
  line-height: 1.5;
}

h3 {
  line-height: 1.5;
}

.banner-image {
  max-width: 80%;
  margin-left: auto;
  margin-right: auto;
  display: block;
}

.main-title {
  font-size: 32px;
  text-align: center;
  font-weight: bold;
}

.main-subtitle {
  text-align: center;
  margin-bottom: 30px;
}
</style>

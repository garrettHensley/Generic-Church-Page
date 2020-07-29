<template>
  <b-container class="mb-4">
    <Nav />
    <b-container class="bg-white">
      <div class="text-center mb-4">
        <b-img src="../logo.png" />
      </div>
      <div>
        <b-img src="../banner.png" fluid />
      </div>
      <b-container class="pb-3">
        <div class="mx-5 text-center d-flex flex-column align-items-center">
          <h2 class="display-4 text-center text-wrap">Food Distribution Event</h2>
          <p
            class="lead"
          >Please join us for our Food Distribution event on August 7th at 2120 Collier Ave Fort Myers, Fl from 1-4pm.</p>
          <b-list-group class="w-50">
            <b-list-group-item variant="primary">Event will include:</b-list-group-item>
            <b-list-group-item>Family Boxes</b-list-group-item>
            <b-list-group-item>Food & Vegetables</b-list-group-item>
          </b-list-group>
        </div>
      </b-container>
      <b-container class="green p-4 text-light">
        <b-row class="nospace">
          <b-col>
            <div class="mb-4">
              <b-img src="../logo2.png" />
            </div>
            <p>6111 South Pointe Blvd</p>
            <p>Fort Myers, Florida 33919</p>
            <p>239.274.8881</p>
          </b-col>
          <b-col>
            <p class="lead">AFFILIATED MINISTRIES</p>
            <p>Word Of Life Freeport, NY</p>
            <p>Stop Hurting Start Healing</p>
            <p>New Life Dream Centers</p>
            <p>Kairos University</p>
            <p>Global Church Fellowship Int'l</p>
            <p>Covenant with Israel Celebration</p>
            <p>GasparandMichele.com</p>
            <p>SWFL Pastors & Leaders Assn.</p>
          </b-col>
          <b-col>
            <div>
              <p class="lead">WEEKLY CALENDAR</p>
              <p class="font-weight-bold">Sundays</p>
              <p>09:00am…Bible Study</p>
              <p>09:00am…Pre-Service Prayer</p>
              <p>10:00am…Corporate gathering</p>
              <p>10:00am…Kids Super Church</p>
            </div>
            <div>
              <p class="font-weight-bold">Tuesdays</p>
              <p>07:00pm…Sacred Marriage Vine Group</p>
            </div>
            <div>
              <p class="font-weight-bold">Wednesdays</p>
              <p>07:00pm…Vine Groups</p>
            </div>
            <div>
              <p class="font-weight-bold">Thursdays</p>
              <p>07:00pm…Kairos University class</p>
            </div>
            <div>
              <p class="font-weight-bold">Fridays</p>
              <p>07:00pm…Friday Service</p>
              <p>07:00pm…Kids Super Church</p>
              <p>07:00pm…Awaken Youth Ministry</p>
            </div>
          </b-col>
          <b-col>
            <p class="lead">RECENT BLOG POSTS</p>
            <p class>
              <em>The Unspoken Addiction July 25, 2020</em>
            </p>
            <p>… The post The Unspoken Addiction appeared first on Gaspar & Michele.</p>
            <p class>
              <em>Racism in the Church, part 2 July 18, 2020</em>
            </p>
            <p>Until we as the body of Christ are willing to join together and look into the mirror of God’s word, we will never see racism done away with. It needs to be eradicated first within us, as Christians, before we can affect the world in which we live. The post Racism in the Church, part […]</p>
            <p class>
              <em>Racism in the Church, part 1 July 11, 2020</em>
            </p>
            <p>Until we as the body of Christ are willing to join together and look into the mirror of God’s word, we will never see racism done away with. It needs to be eradicated first within us, as Christians, before we can affect the world in which we live. The post Racism in the Church, part […]</p>
          </b-col>
        </b-row>
      </b-container>
    </b-container>
  </b-container>
</template>

<script>
import Nav from "@/components/Nav.vue";
export default {
  components: {
    Nav,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&family=Raleway:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

html body {
  background-color: #25705b;
  font-family: "Lato", sans-serif;
  font-weight: 400;
}
.green {
  background-color: #1a5445;
}
.display-1 {
  font-weight: 200;
}
.no-pad {
  padding-left: 0 !important;
  padding-right: 0 !important;
}
.nospace p {
  margin-top: 0.2rem;
  margin-bottom: 0.2rem;
}
.nospace div {
  margin-top: 0.5em;
}
</style>
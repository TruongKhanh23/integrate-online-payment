<template>
  <div>
    <div class="position-relative"></div>
    <section class="section section-lg">
      <div class="container">
        <div class="row row-grid align-items-center">
          <div class="col-md-6 order-md-2">
            <img
              src="img/book/how-to-win-friends.png"
              class="img-fluid floating"
            />
          </div>
          <div class="col-md-6 order-md-1">
            <div class="pr-md-5">
              <icon
                name="ni ni-settings-gear-65"
                class="mb-5"
                size="lg"
                type="success"
                shadow
                rounded
              ></icon>
              <h3>How to Win Friends and Influence People</h3>
              <p>
                You can go after the job you want—and get it! You can take the
                job you have—and improve it! You can take any situation—and make
                it work for you!
              </p>
              <ul class="list-unstyled mt-5">
                <li class="py-2">
                  <div class="d-flex align-items-center">
                    <badge
                      type="success"
                      circle
                      class="mr-3"
                      icon="ni ni-settings-gear-65"
                    ></badge>
                    <h6 class="mb-0">Six ways to make people like you.</h6>
                  </div>
                </li>
                <li class="py-2">
                  <div class="d-flex align-items-center">
                    <badge
                      type="success"
                      circle
                      class="mr-3"
                      icon="ni ni-html5"
                    ></badge>
                    <h6 class="mb-0">
                      Twelve ways to win people to your way of thinking.
                    </h6>
                  </div>
                </li>
                <li class="py-2">
                  <div class="d-flex align-items-center">
                    <badge
                      type="success"
                      circle
                      class="mr-3"
                      icon="ni ni-satisfied"
                    ></badge>
                    <h6 class="mb-0">
                      Nine ways to change people without arousing resentment.
                    </h6>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section section-shaped my-0 overflow-hidden">
      <div class="shape shape-style-3 bg-gradient-default shape-skew">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
      <div class="container pb-300">
        <div class="row text-center justify-content-center">
          <div class="col-lg-10">
            <h2 class="display-3 text-white">
              How to Win Friends & Influence People
            </h2>
            <p class="lead text-white">
              Dale Carnegie’s rock-solid, time-tested advice has carried
              countless people up the ladder of success in their business and
              personal lives. One of the most groundbreaking and timeless
              bestsellers of all time, How to Win Friends & Influence People
              will teach you.
            </p>
          </div>
        </div>
      </div>
    </section>
    <section class="section section-lg pt-lg-0 section-contact-us">
      <div class="container">
        <div class="row justify-content-center mt--300">
          <div class="col-lg-8">
            <card gradient="secondary" shadow body-classes="p-lg-5">
              <h1 class="mb-1 text-center">Buy Now</h1>
              <p class="mt-0 text-center">
                Your project is very important to us.
              </p>
              <base-input
                class="mt-5"
                alternative
                placeholder="Your name"
                addon-left-icon="ni ni-user-run"
              >
              </base-input>
              <base-input
                alternative
                placeholder="Your phone number"
                addon-left-icon="ni ni-satisfied"
              >
              </base-input>
              <base-input
                alternative
                placeholder="Email address"
                addon-left-icon="ni ni-email-83"
              >
              </base-input>
              <base-input class="mb-4">
                <textarea
                  class="form-control form-control-alternative"
                  name="name"
                  rows="4"
                  cols="80"
                  placeholder="Type a message..."
                ></textarea>
              </base-input>
              <base-button type="default" round block size="lg">
                Make payment
              </base-button>
            </card>
          </div>
        </div>
      </div>
    </section>
    <section class="section section-lg">
      <div class="container">
        <div class="row row-grid justify-content-center">
          <div class="col-lg-8 text-center">
            <h2 class="display-3">
              About the Author
              <span class="text-success">Dale Carnegie</span>
            </h2>
            <p class="lead">
              Dale Carnegie (1888-1955) described himself as a "simple country
              boy" from Missouri but was also a pioneer of the self-improvement
              genre. Since the 1936 publication of his first book, How to Win
              Friends and Influence People, he has touched millions of readers
              and his classic works continue to impact lives to this day. Image
              by Dale Carnegie Created in vector format by Scewing (Heritage
              Auctions) [Public domain], via Wikimedia Commons
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "home",
  components: {},
};
</script>

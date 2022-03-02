<template>
  <div class="menu">
    <v-card class="overflow-hidden">
      <v-app-bar
        style="z-index: 9"
        absolute
        color="red lighten-5"
        elevate-on-scroll
        scroll-target="#scrolling-techniques-7"
      >
        <v-app-bar-nav-icon @click.stop="drawer = !drawer"></v-app-bar-nav-icon>

        <v-toolbar-title>Leaning vuetify</v-toolbar-title>

        <v-spacer></v-spacer>

        <v-btn @click="alert = !alert" icon>
          <v-icon>mdi-dots-vertical</v-icon>
        </v-btn>
      </v-app-bar>
      <v-sheet id="scrolling-techniques-7" class="overflow" max-height="634">
        <div class="center">
          <v-alert :value="alert" shaped prominent type="error">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Iusto
            recusandae magni consectetur laborum dignissimos qui minus quidem
            provident rerum obcaecati.
          </v-alert>
        </div>
        <div class="carousel">
          <v-carousel>
            <v-carousel-item
              v-for="(item, i) in items"
              :key="i"
              :src="item.src"
              reverse-transition="fade-transition"
              transition="fade-transition"
            ></v-carousel-item>
          </v-carousel>
        </div>z
        <div class="d-flex cart" style="padding-bottom: 30px">
          <v-col cols="12" style="margin-top: 30px" md="4">
            <v-card class="mx-auto" max-width="400">
              <v-img
                class="white--text align-end"
                height="200px"
                src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
              >
                <v-card-title>Top 10 Australian beaches</v-card-title>
              </v-img>

              <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

              <v-card-text class="text--primary">
                <div>Whitehaven Beach</div>

                <div>Whitsunday Island, Whitsunday Islands</div>
              </v-card-text>

              <v-card-actions>
                <v-btn color="orange" text> Share </v-btn>

                <v-btn color="orange" text> Explore </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col class="ml-2" style="margin-top: 30px" cols="12" md="4">
            <v-card class="mx-auto" max-width="400">
              <v-img
                class="white--text align-end"
                height="200px"
                src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
              >
                <v-card-title>Top 10 Australian beaches</v-card-title>
              </v-img>

              <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

              <v-card-text class="text--primary">
                <div>Whitehaven Beach</div>

                <div>Whitsunday Island, Whitsunday Islands</div>
              </v-card-text>

              <v-card-actions>
                <v-btn color="orange" text> Share </v-btn>

                <v-btn color="orange" text> Explore </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col class="ml-2" style="margin-top: 30px" cols="12" md="4">
            <v-card class="mx-auto" max-width="400">
              <v-img
                class="white--text align-end"
                height="200px"
                src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
              >
                <v-card-title>Top 10 Australian beaches</v-card-title>
              </v-img>

              <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

              <v-card-text class="text--primary">
                <div>Whitehaven Beach</div>

                <div>Whitsunday Island, Whitsunday Islands</div>
              </v-card-text>

              <v-card-actions>
                <v-btn color="orange" text> Share </v-btn>

                <v-btn color="orange" text> Explore </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col class="ml-2" style="margin-top: 30px" cols="12" md="4">
            <v-card class="mx-auto" max-width="400">
              <v-img
                class="white--text align-end"
                height="200px"
                src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
              >
                <v-card-title>Top 10 Australian beaches</v-card-title>
              </v-img>

              <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

              <v-card-text class="text--primary">
                <div>Whitehaven Beach</div>

                <div>Whitsunday Island, Whitsunday Islands</div>
              </v-card-text>

              <v-card-actions>
                <v-btn color="orange" text> Share </v-btn>

                <v-btn color="orange" text> Explore </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col class="ml-2" style="margin-top: 30px" cols="12" md="4">
            <v-card class="mx-auto" max-width="400">
              <v-img
                class="white--text align-end"
                height="200px"
                src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
              >
                <v-card-title>Top 10 Australian beaches</v-card-title>
              </v-img>

              <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

              <v-card-text class="text--primary">
                <div>Whitehaven Beach</div>

                <div>Whitsunday Island, Whitsunday Islands</div>
              </v-card-text>

              <v-card-actions>
                <v-btn color="orange" text> Share </v-btn>

                <v-btn color="orange" text> Explore </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col class="ml-2" style="margin-top: 30px" cols="12" md="4">
            <v-card class="mx-auto" max-width="400">
              <v-img
                class="white--text align-end"
                height="200px"
                src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
              >
                <v-card-title>Top 10 Australian beaches</v-card-title>
              </v-img>

              <v-card-subtitle class="pb-0"> Number 10 </v-card-subtitle>

              <v-card-text class="text--primary">
                <div>Whitehaven Beach</div>
                <div>Whitsunday Island, Whitsunday Islands</div>
              </v-card-text>

              <v-card-actions>
                <v-btn color="orange" text> Share </v-btn>

                <v-btn color="orange" text> Explore </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
        </div>
        <div
          style="margin-bottom:50px width:100%;overflow:hidden"
          class="mb-10 connect"
        >
          <h1 class="t-center" style="text-align: center">Connect us</h1>
          <v-form v-model="valid">
            <v-container style="margin-left: 25%">
              <v-col cols="12" md="4">
                <v-text-field
                  style="width: 50%"
                  v-model="firstname"
                  :rules="nameRules"
                  :counter="10"
                  label="First name"
                  required
                ></v-text-field>
              </v-col>

              <v-col cols="12" md="4">
                <v-text-field
                  style="width: 50%"
                  v-model="lastname"
                  :rules="nameRules"
                  :counter="10"
                  label="Last name"
                  required
                ></v-text-field>
              </v-col>
              <v-col cols="12" md="4">
                <v-text-field
                  style="width: 50%"
                  v-model="email"
                  :rules="emailRules"
                  label="E-mail"
                  required
                ></v-text-field>
              </v-col>
              <v-col cols="12" md="4">
                <v-combobox
                  style="width: 50%"
                  v-model="select"
                  :item="item"
                  label="Enter your Country"
                  multiple
                  outlined
                  dense
                ></v-combobox>
              </v-col>
              <v-col cols="12" md="4">
                <v-textarea
                  style="width: 50%"
                  name="input-7-1"
                  filled
                  label="Enter message"
                  auto-grow
                  value="Write here"
                ></v-textarea>
              </v-col>
              <v-btn
              style="margin-left:18%"
                depressed
                color="primary"
              >
              Sent message
              </v-btn>
            </v-container>
          </v-form>
        </div>
      </v-sheet>
      <v-navigation-drawer style="z-index: 10" v-model="drawer" absolute bottom temporary>
        <v-list nav dense>
          <v-list-item-group
            v-model="group"
            active-class="deep-purple--text text--accent-4"
          >
            <v-list-item>
              <v-list-item-title>Sign up</v-list-item-title>
            </v-list-item>

            <v-list-item>
              <v-list-item-title>Login</v-list-item-title>
            </v-list-item>
          </v-list-item-group>
        </v-list>
      </v-navigation-drawer>
    </v-card>
  </div>
</template>

<script>
export default {
  name: "HOme",
  data() {
    return {
      drawer: false,
      group: null,
      alert: false,
      items: [
        {
          src: "https://wallpaperaccess.com/full/279547.jpg",
        },
        {
          src: "https://www.teahub.io/photos/full/1-13344_2560x1600-hd-laptop-wallpapers-hd-desktop-wallpapers-laptop.jpg",
        },
        {
          src: "https://www.teahub.io/photos/full/55-552795_wallpaper-laptop-macbook-iphone-apple-journal-laptop-hd.jpg",
        },
        {
          src: "https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2016/12/create-quality-wallpapers.jpg",
        },
      ],
      valid: false,
      firstname: "",
      lastname: "",
      nameRules: [
        (v) => !!v || "Name is required",
        (v) => v.length <= 10 || "Name must be less than 10 characters",
      ],
      email: "",
      emailRules: [
        (v) => !!v || "E-mail is required",
        (v) => /.+@.+/.test(v) || "E-mail must be valid",
      ],
      select: ["Bangladesh"],
      item: ["Programming", "Design", "Vue", "Vuetify"],
    };
  },

  watch: {
    group() {
      this.drawer = false;
    },
  },
};
</script>
<style>
.cart {
  flex-wrap: wrap;
}
.carousel {
  margin-top: 65px;
}
.overflow {
  overflow-y: auto;
}
.center {
  position: fixed;
  top: 45%;
  left: 25%;
  width: 50%;
  z-index: 9999;
}
::-webkit-scrollbar {
  width: 3px;
}

/* Track */
::-webkit-scrollbar-track {
  background: #f1f1f1;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: #888;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #555;
}
</style>
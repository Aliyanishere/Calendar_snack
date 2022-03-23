<template>
  <div>
    <div
      class="container subscription justify-content-lg-between p-4 text-center text-lg-start"
    >
      <div class="bg-transparent">
        <p class="fs-5 fw-bold mb-0">
          Get the Calendar Invite directly to your INBOX!
        </p>
        <p class="email">
          Enter your email, pick your events, get the invite, & RSVP
        </p>
      </div>
      <div class="bg-transparent text-center text-lg-start">
        <b-form-input
          v-model="text"
          placeholder="Enter your email"
          class="email_feild"
        ></b-form-input>
      </div>
    </div>

    <div class="container text-center mt-5">
      <p class="mb-0 fw-bold fs-5">View Your Events</p>
      <p class="email">Upcoming Events</p>
    </div>

    <div class="container calendar_cards justify-content-lg-between my-4">
      <div class="calendar_card">
        <div class="card_first_section">
          <div class="date">
            <p class="mb-0" style="border-bottom: 1px solid white">Mar 2022</p>
            <p
              class="mb-0 fs-2 fw-bold"
              style="color: #7eb611; margin-bottom: -2px"
            >
              27
            </p>
            <p class="mb-0 px-4 mt-0">Sunday</p>
          </div>
          <div class="starting_at ms-2">
            <p class="mb-1 fw-bold">Lorem Ipsum dummy text</p>
            <b-form-group v-slot="{ ariaDescribedby }">
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="1"
                >start 9:30 am</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="2"
                >None</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="3"
                >Status: confirmed</b-form-radio
              >
            </b-form-group>
          </div>
        </div>
        <div class="card_second_section">
          <p class="mb-0">0 Invites</p>
          <p class="mb-0">0 RSVPs</p>
          <p class="mb-0">0% response</p>
        </div>
        <button>RSVP</button>
      </div>

      <div class="calendar_card">
        <div class="card_first_section">
          <div class="date">
            <p class="mb-0" style="border-bottom: 1px solid white">Mar 2022</p>
            <p
              class="mb-0 fs-2 fw-bold"
              style="color: #7eb611; margin-bottom: -2px"
            >
              27
            </p>
            <p class="mb-0 px-4 mt-0">Sunday</p>
          </div>
          <div class="starting_at ms-2">
            <p class="mb-1 fw-bold">Lorem Ipsum dummy text</p>
            <b-form-group v-slot="{ ariaDescribedby }">
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="4"
                >start 9:30 am</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="5"
                >None</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="6"
                >Status: confirmed</b-form-radio
              >
            </b-form-group>
          </div>
        </div>
        <div class="card_second_section">
          <p class="mb-0">0 Invites</p>
          <p class="mb-0">0 RSVPs</p>
          <p class="mb-0">0% response</p>
        </div>
        <button>RSVP</button>
      </div>

      <div class="calendar_card">
        <div class="card_first_section">
          <div class="date">
            <p class="mb-0" style="border-bottom: 1px solid white">Mar 2022</p>
            <p
              class="mb-0 fs-2 fw-bold"
              style="color: #7eb611; margin-bottom: -2px"
            >
              27
            </p>
            <p class="mb-0 px-4 mt-0">Sunday</p>
          </div>
          <div class="starting_at ms-2">
            <p class="mb-1 fw-bold">Lorem Ipsum dummy text</p>
            <b-form-group v-slot="{ ariaDescribedby }">
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="7"
                >start 9:30 am</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="8"
                >None</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="9"
                >Status: confirmed</b-form-radio
              >
            </b-form-group>
          </div>
        </div>
        <div class="card_second_section">
          <p class="mb-0">0 Invites</p>
          <p class="mb-0">0 RSVPs</p>
          <p class="mb-0">0% response</p>
        </div>
        <button>RSVP</button>
      </div>

      <div class="calendar_card">
        <div class="card_first_section">
          <div class="date">
            <p class="mb-0" style="border-bottom: 1px solid white">Mar 2022</p>
            <p
              class="mb-0 fs-2 fw-bold"
              style="color: #7eb611; margin-bottom: -2px"
            >
              27
            </p>
            <p class="mb-0 px-4 mt-0">Sunday</p>
          </div>
          <div class="starting_at ms-2">
            <p class="mb-1 fw-bold">Lorem Ipsum dummy text</p>
            <b-form-group v-slot="{ ariaDescribedby }">
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="10"
                >start 9:30 am</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="11"
                >None</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="12"
                >Status: confirmed</b-form-radio
              >
            </b-form-group>
          </div>
        </div>
        <div class="card_second_section">
          <p class="mb-0">0 Invites</p>
          <p class="mb-0">0 RSVPs</p>
          <p class="mb-0">0% response</p>
        </div>
        <button>RSVP</button>
      </div>

      <div class="calendar_card">
        <div class="card_first_section">
          <div class="date">
            <p class="mb-0" style="border-bottom: 1px solid white">Mar 2022</p>
            <p
              class="mb-0 fs-2 fw-bold"
              style="color: #7eb611; margin-bottom: -2px"
            >
              27
            </p>
            <p class="mb-0 px-4 mt-0">Sunday</p>
          </div>
          <div class="starting_at ms-2">
            <p class="mb-1 fw-bold">Lorem Ipsum dummy text</p>
            <b-form-group v-slot="{ ariaDescribedby }">
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="13"
                >start 9:30 am</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="14"
                >None</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="15"
                >Status: confirmed</b-form-radio
              >
            </b-form-group>
          </div>
        </div>
        <div class="card_second_section">
          <p class="mb-0">0 Invites</p>
          <p class="mb-0">0 RSVPs</p>
          <p class="mb-0">0% response</p>
        </div>
        <button>RSVP</button>
      </div>

      <div class="calendar_card">
        <div class="card_first_section">
          <div class="date">
            <p class="mb-0" style="border-bottom: 1px solid white">Mar 2022</p>
            <p
              class="mb-0 fs-2 fw-bold"
              style="color: #7eb611; margin-bottom: -2px"
            >
              27
            </p>
            <p class="mb-0 px-4 mt-0">Sunday</p>
          </div>
          <div class="starting_at ms-2">
            <p class="mb-1 fw-bold">Lorem Ipsum dummy text</p>
            <b-form-group v-slot="{ ariaDescribedby }">
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="16"
                >start 9:30 am</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="17"
                >None</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="18"
                >Status: confirmed</b-form-radio
              >
            </b-form-group>
          </div>
        </div>
        <div class="card_second_section">
          <p class="mb-0">0 Invites</p>
          <p class="mb-0">0 RSVPs</p>
          <p class="mb-0">0% response</p>
        </div>
        <button>RSVP</button>
      </div>

      <div class="calendar_card">
        <div class="card_first_section">
          <div class="date">
            <p class="mb-0" style="border-bottom: 1px solid white">Mar 2022</p>
            <p
              class="mb-0 fs-2 fw-bold"
              style="color: #7eb611; margin-bottom: -2px"
            >
              27
            </p>
            <p class="mb-0 px-4 mt-0">Sunday</p>
          </div>
          <div class="starting_at ms-2">
            <p class="mb-1 fw-bold">Lorem Ipsum dummy text</p>
            <b-form-group v-slot="{ ariaDescribedby }">
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="19"
                >start 9:30 am</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="20"
                >None</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="21"
                >Status: confirmed</b-form-radio
              >
            </b-form-group>
          </div>
        </div>
        <div class="card_second_section">
          <p class="mb-0">0 Invites</p>
          <p class="mb-0">0 RSVPs</p>
          <p class="mb-0">0% response</p>
        </div>
        <button>RSVP</button>
      </div>

      <div class="calendar_card">
        <div class="card_first_section">
          <div class="date">
            <p class="mb-0" style="border-bottom: 1px solid white">Mar 2022</p>
            <p
              class="mb-0 fs-2 fw-bold"
              style="color: #7eb611; margin-bottom: -2px"
            >
              27
            </p>
            <p class="mb-0 px-4 mt-0">Sunday</p>
          </div>
          <div class="starting_at ms-2">
            <p class="mb-1 fw-bold">Lorem Ipsum dummy text</p>
            <b-form-group v-slot="{ ariaDescribedby }">
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="22"
                >start 9:30 am</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="23"
                >None</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="24"
                >Status: confirmed</b-form-radio
              >
            </b-form-group>
          </div>
        </div>
        <div class="card_second_section">
          <p class="mb-0">0 Invites</p>
          <p class="mb-0">0 RSVPs</p>
          <p class="mb-0">0% response</p>
        </div>
        <button>RSVP</button>
      </div>

      <div class="calendar_card">
        <div class="card_first_section">
          <div class="date">
            <p class="mb-0" style="border-bottom: 1px solid white">Mar 2022</p>
            <p
              class="mb-0 fs-2 fw-bold"
              style="color: #7eb611; margin-bottom: -2px"
            >
              27
            </p>
            <p class="mb-0 px-4 mt-0">Sunday</p>
          </div>
          <div class="starting_at ms-2">
            <p class="mb-1 fw-bold">Lorem Ipsum dummy text</p>
            <b-form-group v-slot="{ ariaDescribedby }">
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="A"
                >start 9:30 am</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="B"
                >None</b-form-radio
              >
              <b-form-radio
                class="radio"
                v-model="selected"
                :aria-describedby="ariaDescribedby"
                name="some-radios"
                value="C"
                >Status: confirmed</b-form-radio
              >
            </b-form-group>
          </div>
        </div>
        <div class="card_second_section">
          <p class="mb-0">0 Invites</p>
          <p class="mb-0">0 RSVPs</p>
          <p class="mb-0">0% response</p>
        </div>
        <button>RSVP</button>
      </div>
    </div>

    <div class="footer mt-5 mb-3">
      <p>
        Powered by <span>Calendar Snack,</span> a service of <span>31Events © 2020-2022</span> All Rights
        Reserved
      </p>
    </div>

  </div>
</template>

<script>
export default {
  data() {
    return {
      selected: "2",
    };
  },
};
</script>

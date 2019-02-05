<template>
  <div data-simplebar>
    <h3>Upcoming Events</h3>
    <ul>
      <li v-for="(event, i) in events" :key="i">
        {{ event.title }}
        <br>
        {{ event.description }}
      </li>
    </ul>
    <h3>Archive</h3>
    <ul>
      <li v-for="(event, i) in events" :key="i">
        {{ event.title }}
        <br>
        {{ event.description }}
      </li>
    </ul>
    <ul>
      <li v-for="(event, i) in events" :key="i">
        {{ event.title }}
        <br>
        {{ event.description }}
      </li>
    </ul>
    <ul>
      <li v-for="(event, i) in events" :key="i">
        {{ event.title }}
        <br>
        {{ event.description }}
      </li>
    </ul>
    <ul>
      <li v-for="(event, i) in events" :key="i">
        {{ event.title }}
        <br>
        {{ event.description }}
      </li>
    </ul>
    <ul>
      <li v-for="(event, i) in events" :key="i">
        {{ event.title }}
        <br>
        {{ event.description }}
      </li>
    </ul>
    <ul>
      <li v-for="(event, i) in events" :key="i">
        {{ event.title }}
        <br>
        {{ event.description }}
      </li>
    </ul>
  </div>
</template>

<script>
// import Logo from '~/components/Logo.vue'
// import VuetifyLogo from '~/components/VuetifyLogo.vue'
import 'simplebar'
import 'simplebar/dist/simplebar.css'

export default {
  name: 'Schedule',
  data() {
    return {
      events: [
        {
          title: 'Event #1',
          date: '29102018',
          url: 'https://google.com',
          description: 'Lorem ipsum dolor sit amet.',
          semester: 'Fall 2018'
        },
        {
          title: 'Event #2',
          date: '02112018',
          url: 'https://google.com',
          description: 'Lorem ipsum dolor sit amet.',
          semester: 'Fall 2018'
        },
        {
          title: 'Event #3',
          date: '31122018',
          url: 'https://google.com',
          description: 'Lorem ipsum dolor sit amet.',
          semester: 'Fall 2018'
        },
        {
          title: 'Event #4',
          date: '16022019',
          url: 'https://google.com',
          description: 'Lorem ipsum dolor sit amet.',
          semester: 'Spring 2018'
        },
        {
          title: 'Event #5',
          date: '29102019',
          url: 'https://google.com',
          description: 'Lorem ipsum dolor sit amet.',
          semester: 'Fall 2019'
        }
      ]
    }
  },
  methods: {
    openUrl(url) {
      window.open(url, '_blank')
    }
  }
}
</script>

<style lang="scss">
[data-simplebar] {
  max-width: 100%;
  padding-right: 15px;
}
h3 {
  margin-bottom: 10px;
}
</style>

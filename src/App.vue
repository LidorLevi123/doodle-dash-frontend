<template>
  <section>
    <RouterView/>
  </section>
</template>

<script>
import { userService } from './services/user.service'
import { store } from './store/store'

import AppHeader from './cmps/AppHeader.vue'
import UserMsg from './cmps/UserMsg.vue'


export default {

  created() {
    // console.log('Vue App created')
    // const user = userService.getLoggedinUser()
    // if (user) this.$store.commit({type: 'setLoggedinUser', user})
  },
  components: {
    AppHeader,
    UserMsg
  },
}
</script>
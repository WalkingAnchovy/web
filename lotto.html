<html>
<head>
  <title>Food Battle</title>
  <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <div class="container text-center">
    <p style="font-size: 140px;">
      LOTTO
    </p>

    <div class="row">
      <food @voted="countVote" name="1th ball"></food>
      <food @voted="countVote" name="2th ball"></food>
      <food @voted="countVote" name="3th ball"></food>
      <food @voted="countVote" name="4th ball"></food>
      <food @voted="countVote" name="5th ball"></food>
      <food @voted="countVote" name="6th ball"></food>
      <food @voted="countVote" name="BONUS ball"></food>
    </div>
    <h1>Log:</h1>
    <ul class="list-group">
      <li class="list-group-item" v-for="vote in log"> {{ vote }} </li>
    </ul>
  </div>
</body>
<template id="food">
  <div class="text-center col-sm-2 control-label">
    <p style="font-size: 40px;">
      {{ votes }}
    </p>
    <button class="btn btn-default" @click="vote">{{ name }}</button>
  </div>
</template>
<script src="http://cdnjs.cloudflare.com/ajax/libs/vue/2.3.4/vue.js"></script>
<script type="text/javascript">
  var bus = new Vue()
  var votes;

  Vue.component('food', {
    template: '#food',
    props: ['name'],
    data: function() {
      return {
        votes: '?'
      }
    },
    methods: {
      vote: function(event) {
        console.log(event);
        var a = 0;
        var b = 99;
        this.votes = Math.floor(Math.random() * (b - a + 1) + a)
        votes = this.votes
        this.$emit('voted', event.srcElement.textContent)
      }
    }
  })
  new Vue({
    el: '.container',
    data: {
      votes: '?',
      log: []
    },
    methods:
    {
      countVote: function (food) {
        if(food == 'BONUS ball')
        {
          this.votes = votes;
          this.log.push(food + ' is ' + votes + '!')
        } else {
        this.log.push(food + 'th ball is ' + votes + '!')
        }
      }
    }
  })
</script>
</html>

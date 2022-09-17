<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Мама мне всегда говорила, что "Кто хочет - тот получит",<br>
      Я почти даже с синтаксисом разобрался, <br>
      Но вы были правы - Python круче 😢
    </p>
    <h2>А меня Германом зовут</h2>
    <ul>
      <li><a href="https://vk.com/ilovesmirkin" target="_blank" rel="noopener">ВКонтакте</a></li>
    </ul>
    <h3>Даже разобрался как текстовое поле убрать..</h3>
    <button  @click="but"  id="but"> Смотрите я кнопку сделал!!!! </button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 20px 0 0;
}
button
{
  margin: 30px 0 0;
  display: ruby-text;
  color: #2c3e50;

}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

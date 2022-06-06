<template>
  <div class="container">
    <div class="title">
      <h2>Gerenciamento de Times</h2>
    </div>
    <div class="form-input">
      <input type="text" />
      <button>Salvar</button>
    </div>
    <div class="list-times">
      <table>
        <thead>
          <tr>
            <th>ID</th>
            <th>Nome</th>
            <th>Ações</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>Time 1</td>
            <td>??</td>
          </tr>
          <tr>
            <td>2</td>
            <td>Time 2</td>
            <td>??</td>
          </tr>
          <tr>
            <td>3</td>
            <td>Time 3</td>
            <td>??</td>
          </tr>
          <tr>
            <td>4</td>
            <td>Time 4</td>
            <td>??</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<style>
.title {
  margin-top: 2rem auto;
  display: flex;
  justify-content: center;
}

.form-input {
  margin-top: 10px;
  display: flex;
  justify-content: center;
}

.form-input input {
  width: 60%;
  height: 40px;
  border: 1px solid #ccc;
  border-radius: 10px;
  padding: 0 10px;
}

.form-input button {
  margin-left: 1%;
  width: 15%;
  height: 40px;
  border: 1px solid darkgray;
  border-radius: 10px;
  background-color: darkgray;
  color: white;
  font-weight: bold;
  cursor: pointer;
}
</style>

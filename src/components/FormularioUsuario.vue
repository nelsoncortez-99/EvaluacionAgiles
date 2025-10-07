<template>
  <div class="form-container">
    <h2>Registro de Usuario</h2>
    <form>
      <div class="form-group">
        <label for="nombre">Nombre</label>
        <input type="text" id="nombre" placeholder="Ingrese su nombre" />
      </div>

      <div class="form-group">
        <label for="direccion">Dirección</label>
        <input type="text" id="direccion" placeholder="Ingrese su dirección" />
      </div>

      <div class="form-group">
        <label for="edad">Edad</label>
        <input type="number" id="edad" placeholder="Ingrese su edad" />
      </div>

      <button type="button">Registrar</button>
    </form>
  </div>
</template>
<script>
export default {
  name: 'FormularioUsuario' // 👈 Ahora tiene un nombre de dos palabras
}
</script>
<style scoped>
.form-container {
  max-width: 400px;
  margin: 50px auto;
  background-color: #f4f4f9;
  border-radius: 12px;
  padding: 25px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

h2 {
  text-align: center;
  color: #333;
  margin-bottom: 25px;
  font-weight: 600;
}

.form-group {
  margin-bottom: 15px;
}

label {
  display: block;
  font-weight: 500;
  margin-bottom: 5px;
  color: #555;
}

input {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 8px;
  font-size: 15px;
  transition: border-color 0.3s ease;
}

input:focus {
  border-color: #42b983;
  outline: none;
}

button {
  width: 100%;
  padding: 10px;
  background-color: #42b983;
  color: #fff;
  border: none;
  border-radius: 8px;
  font-weight: 600;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #36a372;
}
</style>

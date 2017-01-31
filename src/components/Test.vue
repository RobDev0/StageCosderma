<template lang="html">
  <div class="test">
    <label for="">Entrez votre critere</label>
    <input type="text">
    <label> Valeur</label>
    <input type="text">
    <div class="input-field col s12">
      <select multiple>
        <option value="" disabled selected>Choose your option</option>
        <option value="1">Option 1</option>
        <option value="2">Option 2</option>
        <option value="3">Option 3</option>
      </select>
      <label>Materialize Multiple Select</label></br></br></br>
    </div>

    <a class="waves-effect waves-light btn">Validez</a></br>
    <a class="waves-effect waves-light btn">Ajoutez un crière</a></br></br>
    <table class="bordered">
  <thead>
    <tr>
        <th data-field="id">Nb vol disponible</th>
        <th data-field="name">Nb vol occupés</th>
        <th data-field="price">Date de sortie 1/Nb</th>
        <th data-field="price">Date de sortie N/Nb</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>X</td>
      <td>Y</td>
      <td>Date</td>
      <td>Date</td>
    </tr>
  </tbody>
</table>

  </div>
</template>

<script>
export default {
  name: 'test',
};
</script>

<style lang="css">

</style>

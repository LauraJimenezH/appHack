<template>
  <div class="form-denuncia">
    <form class="container-fluid">
      <p class="text-left mb-0">Todas unidas lograremos mucho.</p>
      <p style="font-size: 24px" class="text-left">Ficha de Denuncia</p>
      <div class="custom-control custom-checkbox my-1 mr-sm-2 text-left">
        <input type="checkbox" class="custom-control-input" id="customControlInline">
        <label
          class="custom-control-label"
          for="customControlInline"
          style="padding-top: 3px;"
        >Anónimo</label>
      </div>
      <div class="form-group row">
        <label for="colFormLabel" class="col-12 text-left col-form-label">Nombre</label>
        <div class="col-12">
          <input type="email" class="form-control" id="colFormLabel" placeholder="col-form-label">
        </div>
      </div>
      <div class="form-group row">
        <label for="colFormLabel" class="col-12 text-left col-form-label">DNI del acusado</label>
        <div class="col-12">
          <input type="email" class="form-control" id="colFormLabel" placeholder="col-form-label">
        </div>
      </div>
      <div class="form-group row">
        <label for="colFormLabel" class="col-12 text-left col-form-label">Nombre Acusado</label>
        <div class="col-12">
          <input type="email" class="form-control" id="colFormLabel" placeholder="col-form-label">
        </div>
      </div>
      <div class="form-group row">
        <label for="colFormLabel" class="col-12 text-left col-form-label">Lugar</label>
        <div class="col-12">
          <select type="bov" class="form-control" id="colFormLabel" placeholder="col-form-label">
            <option value></option>
          </select>
        </div>
      </div>
      <div class="form-group row">
        <label for="colFormLabel" class="col-12 text-left col-form-label">Tipo de violencia</label>
        <div class="col-12">
          <select type="bov" class="form-control" id="colFormLabel" placeholder="col-form-label">
            <option value></option>
          </select>
        </div>
      </div>
      <div class="form-group">
        <div class="row">
          <label for="exampleFormControlTextarea1" class="text-left col-12">Historia</label>
        </div>
        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
      </div>
      <div class="form-group row">
        <div class="col-9">
          <p style="color:red">*Sólo se mostrará informaciones generales de la denuncia como el nombre, tipo de acoso, ubicación y la historia.</p>
        </div>
         
      </div>
      <div class="form-group">
        <div class="row">
          <button class="offset-1 acept col-10">Aceptar</button>
        </div>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: "FormDenuncia",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
  font-size: 12px;
}

.cam {
  border-radius: 100px !important;
}

button,
button.acept {
  border-style: none;
  background: #613eea;
  box-shadow: 0px 8px 20px rgba(97, 62, 234, 0.32);
  border-radius: 6px;
  color: white;
  padding: 10px;
  font-size: 16px;
}
</style>

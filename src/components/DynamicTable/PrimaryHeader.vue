<template>
    <div class="d-flex gap-10 justify-space-between header align-center">
        <div class="title">
            <img src="../../assets/filter.png" alt="Buscador" class="mr-2"><span>Filtros - Campos</span> 
        </div>
        <div class="search">
            <img src="../../assets/lupa.png" alt="Buscador" height="auto" width="32px" class="mr-2"> <input type="text" placeholder="Buscar">
        </div>
        <div class="pagination d-flex">
            <label for="elements" class="mr-8">Elementos</label>
            <select name="elements" id="elements">
                <option value="50" selected>50</option>
            </select>
        </div>
        <div class="actions-section d-flex gap-10">
            <img src="../../assets/flecha-abajo.png" style="transform: rotate(90deg)" alt="Buscador"  class="mr-2">
            <img src="../../assets/flecha-abajo.png" style="transform: rotate(90deg)" alt="Buscador"  class="mr-2">
            <img src="../../assets/flecha-abajo.png" style="transform: rotate(270deg)" alt="Buscador"  class="mr-2">
            <img src="../../assets/flecha-abajo.png" style="transform: rotate(270deg)" alt="Buscador"  class="mr-2">
        </div>
        <div class="selected-items">
            Seleccionados <strong>12</strong>
        </div>
        
        <div class="actions-section d-flex gap-10">
            <img src="../../assets/add.png" alt="Buscador" height="auto" width="32px" class="mr-2">
            <img src="../../assets/editar.png" alt="Editar" height="auto" width="32px" class="mr-2"> 
            <img src="../../assets/importar.png" alt="Importar" height="auto" width="32px" class="mr-2"> 
            <img src="../../assets/exportar.png" alt="Exportar" height="auto" width="32px" class="mr-2"> 
            <img src="../../assets/delete.png" alt="Eliminar" height="auto" width="32px" class="mr-2"> 
            <img src="../../assets/campana.png" alt="Campaña" height="auto" width="32px" class="mr-2"> 
            
        </div>
    </div>
</template>
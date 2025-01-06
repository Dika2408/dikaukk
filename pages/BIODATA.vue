<template>
    <div class="container mt-10   ">
      <div class="text-center mb-4">
        <h1 class="text-black">BIODATA DIRI</h1>
      </div>
  
      <div class="card shadow-sm">
        <div class="card-body">
          <!-- Informasi -->
          <h3 class="mb-3">INFORMASI</h3>
          <div class="row mb-4">
            <div class="col-md-3 text-center">
                <img src="/assets/dika.jpeg" class="card-img-top" alt="...">
            </div>
            <div class="col-md-9">
              <ul class="list-group">
                <li class="list-group-item">NAMA:DIKA DWI SETIYANTO</li>
                <li class="list-group-item">TEMPAT LAHIR:TASIKMALAYA</li>
                <li class="list-group-item">TTL:24-08-2006</li>
                <li class="list-group-item">AGAMA:Islam</li>
                <li class="list-group-item">ALAMAT:KP.CIWASMANDI</li>
                <li class="list-group-item">NO HP:0895335051836</li>
              </ul>
            </div>
          </div>
  
          <!-- Pendidikan -->
          <h3 class="mb-3">Pendidikan</h3>
          <ul class="list-group mb-4">
            <li v-for="(education, index) in biodata.education" :key="index" class="list-group-item">
              {{ education }}
            </li>
          </ul>
          <ul class="list-group">
            <li v-for="(experience, index) in biodata.experience" :key="index" class="list-group-item">
              {{ experience }}
            </li>
          </ul>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data: function() {
      return {
        biodata: {
          education: [
            'SMK NEGERI 4 TASIKMALAYA 2022-2025',
            'MTS JIDRIS ASSALAM 2019-2022',
            'MTI JIDRIS ASSALAM 2011-2014',
            'DTA NURUL IKHWAN 2005-2011'
          ],
        }
      };
    }
  };
  </script>
  
  <style>
  .container {
    max-width: 700px;
  }
  </style>
  
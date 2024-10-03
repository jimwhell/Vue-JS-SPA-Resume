<script>
export default {
  data() {
    return {
      ProfileName: 'Jimwell Manalo',
      Objective: 'Aspiring and keen web developer seeking to join a team where I can contribute my skills to build engaging and user-friendly websites. Eager to learn and grow in a fast-paced environment.',
      Course: 'Bachelor of Science in Information Techonology',
      Specialization: 'Web Development',
    };
  },
};
</script>
<template>
  <div class="profile-container">
      <div class="container text-center mt-5">
      <div class="profile-text-container">
        <h1>{{ ProfileName }}</h1>
        <h3>Web Developer</h3>

        <div class="contact-section mt-5">
        <ul class="contact-links">
          <li><i class="fa fa-phone"> (096) 512-4925</i></li>
          <li><i class="fa fa-envelope" aria-hidden="true"> jimwelllmanalo@gmail.com</i></li>
        </ul>
      </div>
      </div>

      
      
      <div class="profile-img-container">
        <img src="../assets/images/forrest-gump.jpg" alt="Profile Image">
      </div>

  </div>

    

      <div class="objective-container">
      <hr class="mt-5">
      <div class="text-container">
        <div class="row">
          <div class="col-md-8 mt-5">
            <h2 class="category-title mb-5">Profile</h2> 
            <div class="objective-box">
              <p class="objective-text">{{ Objective }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="course-container">
      <div class="text-container">
        <div class="row">
          <div class="col-md-8 mt-5">
            <div class="objective-box">
              <h5 class="title">Course</h5>
              <p class="objective-text mt-3">{{ Course }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="specialization-container">
      <div class="text-container">
        <div class="row">
          <div class="col-md-8 mt-5">
            <div class="objective-box">
              <h5 class="title">Specialization</h5>
              <p class="objective-text mt-3">{{ Specialization }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>



  </div>
  

  
</template>

<style scoped>
     .profile-img-container {
      width: 150px;
      height: 150px;
      display: flex;
      justify-content: center;
      align-items: center;
      overflow: hidden;
      border-radius: 50%;
      border: none;
    }
    
    .profile-img-container img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .container
    {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    h1
    {
      
    font-family: "Roboto", sans-serif;
    font-weight: 700;
    font-style: normal;
    font-size: 3em;

    }

    .objective-text
    {
      text-align: justify;
    }

    hr
    {
      border: none;
      border-top: 5px solid #000;
    }

    .title
    {
      font-weight: 700;
      text-decoration: underline;
    }

    .category-title
    {
      font-weight: 700;
    }

    .contact-links
    {
      display: flex;
      flex-direction: column;
    }
    
    .contact-links li
    {
      list-style-type: none;
    }


</style>
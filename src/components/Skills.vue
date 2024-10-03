<script>
export default {
    data() {
        return {
            trainings: ['The Odin Project Web Development Course', 'Free Code Camp Responsive Design Course'],
            seminars: ['Introduction to Web Design Principles', 'Git Good: Github Workshop'],
            technologies: ['MySQL', 'HTML5', 'CSS'],
            languages: ['Java', 'Python', 'JavaScript', 'PHP'],
        };
    },
};
</script>

<template>
        <div class="skills-container">
            
      <div class="trainings-container">
      <hr class="mt-5">
      <div class="text-container">
        <div class="row">
          <div class="col-md-8 mt-5">
            <h2 class="category-title mb-5">Skills</h2> 
            <div class="objective-box">
              <h5 class="title">Trainings</h5>
              <ul class="mt-5">
             <li class="mt-4" v-for="(training, index) in trainings" :key="'training-' + index">{{ training }}</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="seminars-container">
      <div class="text-container">
        <div class="row">
          <div class="col-md-8 mt-5">
            <div class="objective-box">
              <h5 class="title">Seminars</h5>
              <ul class="mt-5">
             <li class="mt-4" v-for="(seminar, index) in seminars" :key="'seminar-' + index">{{ seminar }}</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="technologies-container">
      <div class="text-container">
        <div class="row">
          <div class="col-md-8 mt-5">
            <div class="objective-box">
              <h5 class="title">Technologies</h5>
              <ul class="mt-5">
             <li class="mt-4" v-for="(technology, index) in technologies" :key="'technology-' + index">{{ technology }}</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>


    <div class="languages-container mb-5">
      <div class="text-container">
        <div class="row">
          <div class="col-md-8 mt-5">
            <div class="objective-box">
              <h5 class="title">Programming Languages</h5>
              <ul class="mt-5">
             <li class="mt-4" v-for="(language, index) in languages" :key="'language-' + index">{{ language }}</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

</div>
    
</template>

<style scoped>
.skills-container
{
    width: 100%;
}

hr
{
    border: none;
    border-top: 5px solid #000;
}

.education-section
{
    width: 100%;
}

.category-title
{
    font-weight: 700;
}

.title
{
    font-weight: 700;
    text-decoration: underline;
}



</style>
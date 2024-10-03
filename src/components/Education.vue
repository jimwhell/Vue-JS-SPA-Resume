<script>
export default{
    data() {
        return {
            AttendedElemSchool: 'Holy Angel University',
            AttendedJHSSchool: 'Holy Angel University',
            AttendedSHSSchool: 'Holy Angel University,',
            AttendedCollege: 'Holy Angel University'
        }
    },
};

</script>

<template>
    <div class="education-section">
        <div class="elementary-container">
        <hr class="mt-5">
        <h2 class="category-title mt-5">Education</h2>
        <div class="text-container">
            <div class="row">
            <div class="col-md-8 mt-5">
                <div class="objective-box">
                <h5 class="title">Elementary</h5>
                <p class="objective-text mt-3">{{ AttendedElemSchool }}</p>
                </div>
            </div>
            </div>
        </div>
    </div>

    <div class="junior-hs-container">
        <div class="text-container">
            <div class="row">
            <div class="col-md-8 mt-5">
                <div class="objective-box">
                <h5 class="title">Junior High School</h5>
                <p class="objective-text mt-3">{{ AttendedJHSSchool }}</p>
                </div>
            </div>
            </div>
        </div>
    </div>

    <div class="senior-hs-container">
        <div class="text-container">
            <div class="row">
            <div class="col-md-8 mt-5">
                <div class="objective-box">
                <h5 class="title">Senior High School</h5>
                <p class="objective-text mt-3">{{ AttendedSHSSchool}}</p>
                </div>
            </div>
            </div>
        </div>
    </div>

    <div class="senior-hs-container">
        <div class="text-container">
            <div class="row">
            <div class="col-md-8 mt-5">
                <div class="objective-box">
                <h5 class="title">College Education</h5>
                <p class="objective-text mt-3">{{ AttendedCollege}}</p>
                </div>
            </div>
            </div>
        </div>
    </div>
    

    </div>
  
</template>


<style scoped>
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
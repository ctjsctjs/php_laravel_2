<template>
        <div class="jumbotron jumbotron-fluid">
            <div class="container">
                <h1 class="display-6">{{ string.bannerTitle }}</h1>
                <div class="row">
                    <div class="col">
                    <p class="font-weight-normal">{{ string.bannerBody }}</p>
                    </div>
                    <div class="col">
                    </div>
                </div>
                <button type="button" class="btn btn-light">Getting Started</button>
            </div>
        </div>
</template>

<script>
    export default{
        name: 'test',
        data() {
            return {
                string: {
                    bannerTitle: "ValueMax E-Services",
                    bannerBody: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce bibendum varius mauris, sit amet commodo metus condimentum et. Pellentesque maximus mauris id arcu consectetur, ac mattis nibh iaculis. Donec volutpat, augue sit amet lobortis gravida, lectus neque finibus lectus, sit amet mattis enim mi vel erat."
                }
            }
        },
        methods: {
            login: function(){
                alert("login");
            },
        }
    }
</script>
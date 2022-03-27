<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">{{ title }}</div>

                    <div class="card-body">
                        Testando... ok
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        props: {
            title: String
        },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>

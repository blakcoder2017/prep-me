<template>
    <section class="hero is-light is-medium">
        <div class="columns">
            <div class="column">
                <div class="card">
                    <header class="card-header">
                        <p class="card-header-title">
                            Become a Tutor
                        </p>
                    </header>
                    <div class="card-content">
                        <div class="content">
                            <div class="field">
                                <label class="label">First Name</label>
                                <div class="control">
                                    <input 
                                    type="text" 
                                    class="input" 
                                    required 
                                    v-model="newTeacher.firstName">
                                </div>
                            </div>

                            <div class="field">
                                <label class="label">Last Name</label>
                                <div class="control">
                                    <input 
                                    type="text" 
                                    class="input" 
                                    required 
                                    v-model="newTeacher.lastName">
                                </div>
                            </div>

                            <div class="field">
                                <label class="label">Phone</label>
                                <div class="control">
                                    <input 
                                    type="number" 
                                    class="input" 
                                    required 
                                    v-model="newTeacher.phone">
                                </div>
                            </div>

                            <div class="field">
                                <label class="label">Phone</label>
                                <div class="control">
                                    <input 
                                    type="number" 
                                    class="input" 
                                    required 
                                    v-model="newTeacher.phone">
                                </div>
                            </div>
                        </div>
                    </div>
                    <footer class="card-footer">
                        
                            <button class="button is-small is-centered is-primary">Join Us</button>
                       
                    </footer>
                </div>
                
            </div>
            <div class="column">

            </div>
        </div><br/>
    </section>

</template>

<script>
    export default {
        name: 'Become a Tutor',
        data() {
            return {
                newTeacher: {
                    firstName:'',
                    lastName: '',
                    gender: '',
                    phone: '',
                    email: '',
                    userId: '',
                    password:'',
                },
            };
        }
    }
</script>
<style scoped>
    .columns{
        background-image: url('../assets/teacher.jpeg');
        padding:10px;
    }
    #bt1{
        padding: 10px;
    }
</style>
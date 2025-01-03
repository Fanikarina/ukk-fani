<template>
    <div>
        <Header /> 

            <Nav />

                <slot />

        <Footer />
            
    </div>
</template>
<style scoped>
.container{
    max-width: 100%;
    padding: 0;
    margin: 0;
}
</style>
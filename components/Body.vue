<template>
    <div>
        <section class="bod-head">
            <div>
                <button>All time <img src="../assets/cross.svg"></button>
                <button>US, AU, +4 <img src="../assets/cross.svg"></button>
                <button class="btn-more">More Filters <img src="../assets/moredets.svg"></button>
            </div>
                <div class="eyecont">
                    <label for="search"></label>
                    <img src="../assets/search.svg" alt="search" id="eyeimg">
                    <input type="text" name="search" placeholder="Search">
                </div>         
        </section>
        <section>
            <table>
                <tr>
                    <th>cd </th>
                </tr>
            </table>
        </section>
    </div>
</template>

<script>
export default {
    name:'Body',
    data: () =>{
        return{
            
        }
    }
}
</script>
<style lang="scss" scoped>

</style>
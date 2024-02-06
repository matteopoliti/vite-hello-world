<script>
export default {
    name: "AppHero"
}
</script>

<template>
    <div>
        <p>
            Cascading Style Sheets, meglio noto come CSS (in italiano fogli di stile a cascata), è un linguaggio usato per
            definire la formattazione di documenti HTML, XHTML e XML, ad esempio i siti web e relative pagine web. Le regole
            per comporre il CSS sono contenute in un insieme di direttive (Recommendations) emanate a partire dal 1996 dal
            W3C.
        </p>
        <button>Learn more!</button>
    </div>
</template>

<style scoped>
div {
    background: url(../assets/css-full-page-background2.png) no-repeat;
    background-size: cover;
    background-position: center;
    height: 600px;
    position: relative;
    padding: 10px;
}

p {
    font-size: 18px;
    color: #fff;
    text-align: center;
}

button {
    background-color: #26d2ff;
    padding: 10px;
    border-radius: 10px;
    border: none;
    outline: none;
    font-size: 20px;
    font-weight: bold;
    position: absolute;
    bottom: 20px;
    left: 50%;
    transform: translateX(-50%);
    cursor: pointer;
}
</style>
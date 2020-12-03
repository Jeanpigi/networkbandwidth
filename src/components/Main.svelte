<script lang="ts">

    let mega: number = 0;

    const bit: number = 8;

    let bandwidth: number;

</script>

<style>
    .main {
        width: 100vw;
        height: 100vh;
        padding: 3rem;
    }

    ul {
        padding: 1rem;
    }

    li {
        font-size: 1.6rem;
        font-weight: 400;
        font-family: 'Roboto', sans-serif;
        text-align: justify;
    }

    span, p {
        font-size: 1.6rem;
        padding-top: 1rem;
        font-family: 'Roboto', sans-serif;
    }

    .card {
        display: grid;
        justify-content: center;
        align-items: center;
    }

    .card label {
        margin-top: 3rem;
    }
</style>

<main class="main">

    <h1>Mitos de la conexión a Internet que pagas en casa</h1>

    <ul>
        <li>⚡ Los megas determinan tu velocidad. Falso. Tu velocidad es el ping.</li>
        <li>🌊 El internet que consumes llega a través de antenas. Falso. El internet se mueve alrededor del mundo a través de cables submarinos.</li>
        <li>🔎  Speedtest.net es la mejor forma de medir tu internet. Falso. La mejor opción es <a href="https://fast.com/" target="_blank">fast .com.</a></li>
        <li>📞  No puedo mejorar mi conexión. Falso. Tu proveedor hará todo lo posible para que no te vayas del contrato. Llama y reclama si no recibes lo que estás pagando.</li>
    </ul>

    <p>La mayoria cree que las megas que ofrecen los provedores de internet, representa la velocidad de conexión, pero lastimosamente no es así. Y esto es debido a que al igual que en la fisica, la velocidad es la magnitud de carácter vectorial que relaciona el cambio de posición con el tiempo. Sin embargo el valor que ofrecen ya sea 1,2,3,4,5,6,7,8,9,10 megas no tiene nada que ver con velocidad. Comenzando con el verdadero valor. Para esto debemos entender que es un bit. Los computadores entienden 1 y 0. Se denomina lenguaje binario. El bit puede ser cualquiera de esos dos valores. Ahora cuando se tiene un grupo de 8 bits, esta adquiere un nombre llamado Byte. Lo que significa que cuando observas mb/s son bits y cuando ves MB/s son bytes.  </p>

    <div class="card">
        <label for="megas">
            <span>Escribe el número de megabits que tienes</span>
            <input id="megas" bind:value={mega} type="number" >
        </label>

        <h2>{bandwidth = mega / bit } MB/s</h2>
    </div>

</main>

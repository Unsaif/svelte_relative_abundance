<script>
    import BubbleChart from '../D3/bubbleChart'
    // import sample from '../data/sample.csv'
    import * as d3 from "d3"
    import { csv } from "d3";
    import { onMount } from "svelte";

    // async function getCSV() {
    //     const data = await d3.csv('data/sample.csv');
    //     console.log(data)
    //     return data
    // }

    // console.log(getCSV())

//     let dataset = [];
//   onMount(async () => {
//     dataset = await csv("data/sample.csv").then((data) => {
//       return data.slice(0, 10);
//     });
//   });
//   console.log(dataset)
    

    
    // d3.csv(sample, function(d){
    //     console.log(d)
    //     if ( d.value !== '0.0' ){
    //         return {
    //             id: d.id,
    //             value: +d.value
    //         }
    //     }
    // }).then(function(files) {
    //     let chart = BubbleChart(files, {
    //         label: d => [...d.id.split(".").pop().split(/(?=[A-Z][a-z])/g), d.value.toLocaleString("en")].join("\n"),
    //         value: d => d.value,
    //         group: d => d.id.split(".")[1],
    //         title: d => `${d.id}\n${d.value.toLocaleString("en")}`,
    //         link: d => `https://github.com/prefuse/Flare/blob/master/flare/src/${d.id.replace(/\./g, "/")}.as`,
    //         width: 1152
    //     })

    //     d3.select("#chart").node().appendChild(chart)
    // })
</script>

<div id="chart"></div>
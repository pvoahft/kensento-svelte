<script>
	import { test } from '@playwright/test';
	import Btn from './btn.svelte';
	export let cardTitle = '';
    let classStage = 'active';
    
</script>

<div class="card">
	<div class="card-title-{classStage}">
		<h2>{cardTitle}</h2>
	</div>
    <div class="card-price">
        <h2>1000</h2>
        <p>per Month</p>
    </div>
    <p>Plan Includes</p>
    <ul>
        
        <div class="bullet">
            <img src="/graphics/checkbox.svg" alt="check">
            <p>Analyitc Dash Board</p>
        </div>
    </ul>
</div>
div#id-01>div>img

<Btn btnType={'secondary'} btnName={'Get Started'} linkUrl={'#'} />


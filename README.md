# select-options-and-search-by-id
there will be a form and willl have multiple options by selecting will get results
there will be there buttons category,select ,go
// API Reference: https://www.wix.com/velo/reference/api-overview/introduction
// “Hello, World!” Example: https://learn-code.wix.com/en/article/1-hello-world
import {local} from 'wix-storage';
import wixLocation from 'wix-location';
$w.onReady(function () {




});



let categoryVal = ''
export function dropdown5_click(event) {
if($w('#dropdown5').value==='age'){
	$w('#dropdown6').placeholder = "Choose Age"
	$w('#dropdown6').options= [
		{label: '2 yrs',value: '2 yrs'},
		{label: '3-4 yrs',value: '3-4 yrs'},
		{label: '4-5 yrs',value: '4-5 yrs'},
		{label: '5-8 yrs',value: '5-8 yrs'},
		{label: '7-9 yrs',value: '7-9 yrs'},
		{label: '9-11 yrs',value: '9-11 yrs'},
		{label: '11-14 yrs',value: '11-14 yrs'},
		{label: '15+ yrs',value: '15+ yrs'},
	]
}
if($w('#dropdown5').value==='height'){
	$w('#dropdown6').placeholder = "Choose Height"
	$w('#dropdown6').options= [
		{label: '2.9f - 3.11f',value: '2.9f - 3.11f'},
		{label: '3.1f - 3.3f',value: '3.1f - 3.3f'},
		{label: '3.3f" - 3.7f',value: '3.3f" - 3.7f'},
		{label: '3.7f" - 4.0f',value: '3.7f" - 4.0f'},
		{label: '4.0f - 4.5f',value: '4.0f - 4.5f'},
		{label: '4.5f - 4.9f',value: '4.5f - 4.9f'},
		{label: '5+',value: '5+'},
		
	]
}




if($w('#dropdown5').value==='cyclesize'){

	$w('#dropdown6').placeholder = "Choose Cycle Size"
	$w('#dropdown6').options= [
		{label: '10',value: '10'},
		{label: '12',value: '12'},
		{label: '14',value: '14'},
		{label: '16',value: '16'},
		{label: '20',value: '20'},
		{label: '24',value: '24'},
		{label: '26',value: '26'},
		{label: '27.5',value: '27.5'},
		{label: '29',value: '29'},
		
	]
}
}
export function button18_click(event) {
 

}
export function dropdown6_click(event) {
	categoryVal = $w('#dropdown6').value

}
export function button22_click(event) {

	local.setItem("id", categoryVal);
	    wixLocation.to("https://www.radiantcpl.com/bicyles") 
}

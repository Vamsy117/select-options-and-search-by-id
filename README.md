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

// API Reference: https://www.wix.com/velo/reference/api-overview/introduction
// “Hello, World!” Example: https://learn-code.wix.com/en/article/1-hello-world
import { local } from 'wix-storage';
const twoYrs = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_97329504d097424d90ed939b2f0cefe8~mv2.jpg', 'title': 'Tricycle' },
]

const threetofourYrs = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_2d6bf26a1b124b158423fd4f7fcc216c~mv2.jpg', 'title': 'Amaze Pro' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_92827c1576f2452188b92a9a80d30c2f~mv2.jpg', 'title': 'Flash' },

]

const fourtofiveYrs = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_2d6bf26a1b124b158423fd4f7fcc216c~mv2.jpg', 'title': 'Amaze Pro' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_92827c1576f2452188b92a9a80d30c2f~mv2.jpg', 'title': 'Flash' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_4cbc1e866fd54fdd95f8c20c834b697e~mv2.jpg', 'title': 'Odin' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 2.0' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_f9e77a3e8e5a49cb8e69fe9af34470db~mv2.jpg', 'title': 'i-Amaze' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_654ca19450ab45c4be30437597592ca2~mv2.jpg', 'title': 'Amaze Kiah' },

]
const fivetoeightYrs = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_2d6bf26a1b124b158423fd4f7fcc216c~mv2.jpg', 'title': 'Amaze Pro' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_92827c1576f2452188b92a9a80d30c2f~mv2.jpg', 'title': 'Flash' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_4cbc1e866fd54fdd95f8c20c834b697e~mv2.jpg', 'title': 'Odin' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 2.0' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_f9e77a3e8e5a49cb8e69fe9af34470db~mv2.jpg', 'title': 'i-Amaze' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_654ca19450ab45c4be30437597592ca2~mv2.jpg', 'title': 'Amaze Kiah' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 3.0' },

]


const seventonineYrs = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_2d6bf26a1b124b158423fd4f7fcc216c~mv2.jpg', 'title': 'Amaze Pro' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_7b22d3f0375548529ea5292bf5b15e46~mv2.jpg', 'title': 'Zander' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_4cbc1e866fd54fdd95f8c20c834b697e~mv2.jpg', 'title': 'Odin' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 2.0' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_f9e77a3e8e5a49cb8e69fe9af34470db~mv2.jpg', 'title': 'i-Amaze' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_654ca19450ab45c4be30437597592ca2~mv2.jpg', 'title': 'Amaze Kiah' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 3.0' },

]

const ninetoelevenYrs = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b22e5c6bb814462c8883084430f3770d~mv2.jpg', 'title': 'Zephyr' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_47ba0de1cae74178b407999a1c9a6344~mv2.jpg', 'title': 'Zeus' },
	{ 'src': 'https://static.wixstatic.com/media/cd5b69_aa8442085fa34a1ea367026e18e9799e~mv2.jpg', 'title': 'Meraki' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_8448794df910461bbe5104988832b3e0~mv2.jpg', 'title': 'Zeus 3.0' },
	    { 'src': 'https://static.wixstatic.com/media/cd5b69_55d3ace0410b45e7aaf93e8711835542~mv2.jpg', 'title': 'Megatron' },
	    { 'src': 'https://static.wixstatic.com/media/cd5b69_55d3ace0410b45e7aaf93e8711835542~mv2.jpg', 'title': 'Megatron IBC' },

]

const eleventofourtenYrs = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b22e5c6bb814462c8883084430f3770d~mv2.jpg', 'title': 'Zephyr' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_47ba0de1cae74178b407999a1c9a6344~mv2.jpg', 'title': 'Zeus' },
	{ 'src': 'https://static.wixstatic.com/media/cd5b69_aa8442085fa34a1ea367026e18e9799e~mv2.jpg', 'title': 'Meraki' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_8448794df910461bbe5104988832b3e0~mv2.jpg', 'title': 'Zeus 3.0' },
	    { 'src': 'https://static.wixstatic.com/media/cd5b69_55d3ace0410b45e7aaf93e8711835542~mv2.jpg', 'title': 'Megatron' },
	    { 'src': 'https://static.wixstatic.com/media/cd5b69_55d3ace0410b45e7aaf93e8711835542~mv2.jpg', 'title': 'Megatron IBC' },

]
const fifteenYrs = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2f1267d84a44103aad2f94d2bb0f087~mv2.jpg', 'title': 'Zepellin' },
    

]


const twoftothree = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_97329504d097424d90ed939b2f0cefe8~mv2.jpg', 'title': 'Tricycle' },
]

const threeftothreee = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_2d6bf26a1b124b158423fd4f7fcc216c~mv2.jpg', 'title': 'Amaze Pro' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_92827c1576f2452188b92a9a80d30c2f~mv2.jpg', 'title': 'Flash' },

]

const threertoseven = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_2d6bf26a1b124b158423fd4f7fcc216c~mv2.jpg', 'title': 'Amaze Pro' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_92827c1576f2452188b92a9a80d30c2f~mv2.jpg', 'title': 'Flash' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_4cbc1e866fd54fdd95f8c20c834b697e~mv2.jpg', 'title': 'Odin' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 2.0' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_f9e77a3e8e5a49cb8e69fe9af34470db~mv2.jpg', 'title': 'i-Amaze' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_654ca19450ab45c4be30437597592ca2~mv2.jpg', 'title': 'Amaze Kiah' },

]


const threeseventofour = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_2d6bf26a1b124b158423fd4f7fcc216c~mv2.jpg', 'title': 'Amaze Pro' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_92827c1576f2452188b92a9a80d30c2f~mv2.jpg', 'title': 'Flash' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_4cbc1e866fd54fdd95f8c20c834b697e~mv2.jpg', 'title': 'Odin' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 2.0' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_f9e77a3e8e5a49cb8e69fe9af34470db~mv2.jpg', 'title': 'i-Amaze' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_654ca19450ab45c4be30437597592ca2~mv2.jpg', 'title': 'Amaze Kiah' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 3.0' },

]


const fourtofive = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_2d6bf26a1b124b158423fd4f7fcc216c~mv2.jpg', 'title': 'Amaze Pro' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_7b22d3f0375548529ea5292bf5b15e46~mv2.jpg', 'title': 'Zander' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_4cbc1e866fd54fdd95f8c20c834b697e~mv2.jpg', 'title': 'Odin' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 2.0' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_f9e77a3e8e5a49cb8e69fe9af34470db~mv2.jpg', 'title': 'i-Amaze' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_654ca19450ab45c4be30437597592ca2~mv2.jpg', 'title': 'Amaze Kiah' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 3.0' },

]

const fourtofivenine = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b22e5c6bb814462c8883084430f3770d~mv2.jpg', 'title': 'Zephyr' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_47ba0de1cae74178b407999a1c9a6344~mv2.jpg', 'title': 'Zeus' },
	{ 'src': 'https://static.wixstatic.com/media/cd5b69_aa8442085fa34a1ea367026e18e9799e~mv2.jpg', 'title': 'Meraki' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_8448794df910461bbe5104988832b3e0~mv2.jpg', 'title': 'Zeus 3.0' },
	    { 'src': 'https://static.wixstatic.com/media/cd5b69_55d3ace0410b45e7aaf93e8711835542~mv2.jpg', 'title': 'Megatron' },
	    { 'src': 'https://static.wixstatic.com/media/cd5b69_55d3ace0410b45e7aaf93e8711835542~mv2.jpg', 'title': 'Megatron IBC' },

]


const fiveplus = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b22e5c6bb814462c8883084430f3770d~mv2.jpg', 'title': 'Zephyr' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_47ba0de1cae74178b407999a1c9a6344~mv2.jpg', 'title': 'Zeus' },
	{ 'src': 'https://static.wixstatic.com/media/cd5b69_aa8442085fa34a1ea367026e18e9799e~mv2.jpg', 'title': 'Meraki' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_8448794df910461bbe5104988832b3e0~mv2.jpg', 'title': 'Zeus 3.0' },
	    { 'src': 'https://static.wixstatic.com/media/cd5b69_55d3ace0410b45e7aaf93e8711835542~mv2.jpg', 'title': 'Megatron' },
	    { 'src': 'https://static.wixstatic.com/media/cd5b69_55d3ace0410b45e7aaf93e8711835542~mv2.jpg', 'title': 'Megatron IBC' },
		 { 'src': 'https://static.wixstatic.com/media/cd5b69_b2f1267d84a44103aad2f94d2bb0f087~mv2.jpg', 'title': 'Zepellin' },

]

const ten = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_97329504d097424d90ed939b2f0cefe8~mv2.jpg', 'title': 'Tricycle' },
]


const twelve = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_2d6bf26a1b124b158423fd4f7fcc216c~mv2.jpg', 'title': 'Amaze Pro' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_92827c1576f2452188b92a9a80d30c2f~mv2.jpg', 'title': 'Flash' },

]
const fourteen = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_2d6bf26a1b124b158423fd4f7fcc216c~mv2.jpg', 'title': 'Amaze Pro' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_92827c1576f2452188b92a9a80d30c2f~mv2.jpg', 'title': 'Flash' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_4cbc1e866fd54fdd95f8c20c834b697e~mv2.jpg', 'title': 'Odin' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 2.0' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_f9e77a3e8e5a49cb8e69fe9af34470db~mv2.jpg', 'title': 'i-Amaze' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_654ca19450ab45c4be30437597592ca2~mv2.jpg', 'title': 'Amaze Kiah' },

]

const sixteen = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_2d6bf26a1b124b158423fd4f7fcc216c~mv2.jpg', 'title': 'Amaze Pro' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_92827c1576f2452188b92a9a80d30c2f~mv2.jpg', 'title': 'Flash' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_4cbc1e866fd54fdd95f8c20c834b697e~mv2.jpg', 'title': 'Odin' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 2.0' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_f9e77a3e8e5a49cb8e69fe9af34470db~mv2.jpg', 'title': 'i-Amaze' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_654ca19450ab45c4be30437597592ca2~mv2.jpg', 'title': 'Amaze Kiah' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 3.0' },

]
const twenty = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_2d6bf26a1b124b158423fd4f7fcc216c~mv2.jpg', 'title': 'Amaze Pro' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_7b22d3f0375548529ea5292bf5b15e46~mv2.jpg', 'title': 'Zander' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_4cbc1e866fd54fdd95f8c20c834b697e~mv2.jpg', 'title': 'Odin' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 2.0' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_f9e77a3e8e5a49cb8e69fe9af34470db~mv2.jpg', 'title': 'i-Amaze' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_654ca19450ab45c4be30437597592ca2~mv2.jpg', 'title': 'Amaze Kiah' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2554f662b7149f5b0dc3ee4ca39811f~mv2.jpg', 'title': 'Enzo 3.0' },

]
const twentyfour = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b22e5c6bb814462c8883084430f3770d~mv2.jpg', 'title': 'Zephyr' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_47ba0de1cae74178b407999a1c9a6344~mv2.jpg', 'title': 'Zeus' },
	{ 'src': 'https://static.wixstatic.com/media/cd5b69_aa8442085fa34a1ea367026e18e9799e~mv2.jpg', 'title': 'Meraki' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_8448794df910461bbe5104988832b3e0~mv2.jpg', 'title': 'Zeus 3.0' },
	    { 'src': 'https://static.wixstatic.com/media/cd5b69_55d3ace0410b45e7aaf93e8711835542~mv2.jpg', 'title': 'Megatron' },
	    { 'src': 'https://static.wixstatic.com/media/cd5b69_55d3ace0410b45e7aaf93e8711835542~mv2.jpg', 'title': 'Megatron IBC' },

]

const twentysix = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b22e5c6bb814462c8883084430f3770d~mv2.jpg', 'title': 'Zephyr' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_47ba0de1cae74178b407999a1c9a6344~mv2.jpg', 'title': 'Zeus' },
	{ 'src': 'https://static.wixstatic.com/media/cd5b69_aa8442085fa34a1ea367026e18e9799e~mv2.jpg', 'title': 'Meraki' },
    { 'src': 'https://static.wixstatic.com/media/cd5b69_8448794df910461bbe5104988832b3e0~mv2.jpg', 'title': 'Zeus 3.0' },
	    { 'src': 'https://static.wixstatic.com/media/cd5b69_55d3ace0410b45e7aaf93e8711835542~mv2.jpg', 'title': 'Megatron' },
	    { 'src': 'https://static.wixstatic.com/media/cd5b69_55d3ace0410b45e7aaf93e8711835542~mv2.jpg', 'title': 'Megatron IBC' },

]
const twentyseven = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2f1267d84a44103aad2f94d2bb0f087~mv2.jpg', 'title': 'Zepellin' },
    

]


const twentynine = [
    { 'src': 'https://static.wixstatic.com/media/cd5b69_b2f1267d84a44103aad2f94d2bb0f087~mv2.jpg', 'title': 'Zepellin' },
    

]

$w.onReady(function () {
    let items = []
    if (local.getItem("id") === '2 yrs') {
        items = twoYrs
    }
    if (local.getItem("id") === '3-4 yrs') {
        items = threetofourYrs
    }
    if (local.getItem("id") === '4-5 yrs') {
        items = fourtofiveYrs
    }
    if (local.getItem("id") === '5-8 yrs') {
        items = fivetoeightYrs
    }
	if (local.getItem("id") === '7-9 yrs') {
        items = seventonineYrs 

    }

	if (local.getItem("id") === '9-11 yrs') {
        items = ninetoelevenYrs

    }
	
	if (local.getItem("id") === '11-14 yrs') {
        items = eleventofourtenYrs

    }
	if (local.getItem("id") === '15+ yrs') {
        items = fifteenYrs
    }
if (local.getItem("id") === '2.9f - 3.11f') {
        items = twoftothree
    }

	if (local.getItem("id") === '3.1f - 3.3f') {
        items = threeftothreee
    }
if (local.getItem("id") === '3.3f - 3.7f') {
        items = threertoseven
    }

if (local.getItem("id") === '3.7f - 4.0f') {
        items = threeseventofour

    }
if (local.getItem("id") === '4.0f - 4.5f') {
        items = fourtofive


    }

if (local.getItem("id") === '4.5f - 4.9f') {
        items = fourtofivenine

    }

if (local.getItem("id") === '5+') {
        items = fiveplus


    }
if (local.getItem("id") === '10') {
        items = ten


    }



if (local.getItem("id") === '12') {
        items = twelve


    }


if (local.getItem("id") === '14') {
        items = fourteen


    }


if (local.getItem("id") === '16') {
        items = sixteen


    }


if (local.getItem("id") === '20') {
        items = twenty


    }


if (local.getItem("id") === '24') {
        items = twentyfour


    }

if (local.getItem("id") === '26') {
        items = twentysix


    }
	
	if (local.getItem("id") === '27.5') {
        items = twentyseven


    }
	if (local.getItem("id") === '29') {
        items = twentynine


    }

    $w('#gallery1').items = items
    // Write your JavaScript here

    // To select an element by ID use: $w("#elementID")

    // Click "Preview" to run your code
});





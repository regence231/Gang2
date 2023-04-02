<!DOCTYPE html>
<html>
<head>
	<title>Water Catching Game</title>
	<style>
		body {
			background-color: #ADD8E6;
			margin: 0;
			padding: 0;
			font-family: Arial, sans-serif;
		}
		
		h1 {
			margin: 20px;
			text-align: center;
			color: #FFF;
			text-shadow: 2px 2px #000;
		}
		
		.container {
			display: flex;
			flex-wrap: wrap;
			justify-content: center;
			align-items: center;
			height: 100vh;
		}
		
		#bucket {
			position: relative;
			margin: 20px;
			width: 100px;
			height: 150px;
			background-color: #FFF;
			border: 2px solid #000;
			border-radius: 0 0 50% 50%;
			overflow: hidden;
			box-shadow: 2px 2px #000;
			z-index: 1;
		}
		
		#water {
			position: absolute;
			top: 0;
			left: 50%;
			transform: translateX(-50%);
			width: 20px;
			height: 20px;
			background-color: #00F;
			border-radius: 50%;
			animation: falling 2s linear infinite;
			z-index: 0;
		}
		
		@keyframes falling {
			0% {
				top: -20px;
			}
			100% {
				top: calc(100% - 150px);
			}
		}
		
		#backpack {
			position: relative;
			margin: 20px;
			width: 100px;
			height: 150px;
			background-color: #FFF;
			border: 2px solid #000;
			border-radius: 0 0 50% 50%;
			overflow: hidden;
			box-shadow: 2px 2px #000;
			z-index: 1;
		}
		
		#xp {
			position: absolute;
			top: 20px;
			left: 20px;
			font-size: 24px;
			font-weight: bold;
			color: #FFF;
			text-shadow: 1px 1px #000;
		}
		
		#level {
			position: absolute;
			top: 20px;
			right: 20px;
			font-size: 24px;
			font-weight: bold;
			color: #FFF;
			text-shadow: 1px 1px #000;
		}
		
		#prestige {
			position: absolute;
			bottom: 20px;
			left: 20px;
			font-size: 24px;
			font-weight: bold;
			color: #FFF;
			text-shadow: 1px 1px #000;
		}
		
		#rebirth {
			position: absolute;
			bottom: 20px;
			right: 20px;
			font-size: 24px;
			font-weight: bold;
			color: #FFF;
			text-shadow: 1px 1px #000;
		}
		
		.btn {
			display: inline-block;
			padding: 10px 20px;
			margin: 20px;
			background-color: #FFF;
			border: none;
			border-radius: 5px;
			box-shadow

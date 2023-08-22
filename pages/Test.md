---
title: Test
permalink: /permalink/
description: ""
---
<p id="fadly123">This is a Paragraph</p>

<style>
		#fadly123 {
				background-color: white;
				color: darkblue;
				font-size: 18px;
				font-family: Arial, sans-serif;
				padding: 10px;
				border: 2px solid black;
				text-align: center;
				width: 300px;
				margin: 0 auto;
				line-height: 1.6;
				text-transform: uppercase;
				font-weight: bold;
				box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
				border-radius: 10px;
				transition: background-color 0.3s ease-in-out, color 0.3s ease-in-out, transform 0.2s;
				cursor: pointer;
				position: relative;
				z-index: 1;
				overflow: hidden;
		}
		#fadly123:hover {
				background-color: gold;
				color: blue;
				transform: scale(1.1) rotate(3deg);
				box-shadow: 4px 4px 8px rgba(0, 0, 0, 0.4);
				z-index: 2;
		}
		#fadly123::before {
				position: absolute;
				top: -10px;
				left: 50%;
				transform: translateX(-50%);
				font-size: 24px;
		}
		#fadly123::after {
				position: absolute;
				top: 0;
				left: 0;
				width: 100%;
				height: 100%;
				background: linear-gradient(45deg, rgba(255, 255, 255, 0), rgba(255, 255, 255, 0.5) 50%);
				pointer-events: none;
				opacity: 0;
				transition: opacity 0.3s ease-in-out;
		}
		#fadly123:hover::after {
				opacity: 1;
		}
</style>
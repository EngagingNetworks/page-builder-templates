Our newest "Free & Flexible page template V2" by 4Site.

Here are some extra things you might want to try:

**Add a currency symbol and centre the Donation Other box**

```css
.en__field--donationAmt .en__field__item--other:before {
	    content: "£";
	    position: absolute;
	    top: 47%;
	    /* content: ""; */
	    left: 16px;
	    font-size: 16px;
	    transform: translateY(-50%);
	    color: #107783;
	}
	input.en__field__input.en__field__input--other {
		text-align: center !important;
	}
 ```
 
 The templates use variables to control much of the styling. Many of these are exposed in the Blueprint, but not everything. 
 If you want to set a variable to something else, just add it to the <body> tab like many of the others have. 
 For example (with your own values), 

  ```css
--donation-amount__button_count: 3; /* the number of buttons in a row */
--donation-amount__button_font-family: Anton,Impact; /* the donation buttons' font */
--donation-amount__button_border-width: 2px; /* the donation buttons' border width */
--donation-amount__button_border-color: black; /* the donation buttons' border color */
--donation-amount__button_border-radius: 0; /* the donation buttons' border radius */
--click-to-expand__copy-area_height: 200px; /* the height of the expandable readmore area */
 ```

# Additional-Custom-Modules
A simple, tiny additional custom modules to my own liking. I created this repo solely because I want to use it easily with Sine. 

<img width="1365" height="711" alt="image" src="https://github.com/user-attachments/assets/67f97c28-99db-493a-94ea-02ed4d1adf63" />


### Features

- Custom Toolbar Icon
- Modified Window Control Button
- Clean New Tab Button
- Color and URL Bar Tweaks
- Vertical Line for Folders

This is just my personal repository. All of the original codes belong to each their respective owners. I only modified them to fits my needs.

### Credits
- [Zen Minimal Exit Menu](https://github.com/Dinno-DEV/zen-minimal-exit-menu) by Dinno-DEV
- [Zen Better New Tab Button](https://github.com/themaster5209/zen-better-new-tab-button) by themaster5209
- [Arcline](https://github.com/ferrocyante/Arcline) by ferrocyante
- [Transparent Zen](https://github.com/sameerasw/zen-themes/tree/main/TransparentZen) by sameerasw
- https://icon-sets.iconify.design/ SVG used for Custom Toolbar Icon

### Custom CSS Snippets for Bonjourr
I use Bonjourr for my newtab page, and I decided to sprinkle some CSS on top of it because why not. Putting this here so I wont lose it for whatever reason.

<details>
	
<summary> Show CSS </summary>

```css
/* =====Quick Link Hover Effect===== */
.link {
  transition: transform 0.2s cubic-bezier(0.4, 0, 0.2, 1), 
              filter 0.3s cubic-bezier(0.4, 0, 0.2, 1) !important;
  transform: scale(1) translateY(0) !important;
  filter: none !important;
}

.link:hover {
  transform: scale(1.7) translateY(-8px) !important;
  filter: drop-shadow(0 0 4px rgba(255, 255, 255, 0.3)) !important;
  z-index: 1;
}
/* this code broke the moving by draging feature */



/* =====Quick Link BG Styling===== */
/* Glass Effect */
.link-list {
  background-color: rgba(255, 255, 255, 0.08);
  border-radius: 25px;
  backdrop-filter: blur(12px) saturate(150%);
  -webkit-backdrop-filter: blur(12px) saturate(150%);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  position: relative;
  padding: 8px;
	}
	
/* Shiny Line Effect */
.link-list::before {
  content: "";
  position: absolute;
  inset: -1px;
  border-radius: inherit;
  padding: 1.5px;
  background: linear-gradient(
    to bottom,
    rgba(255, 255, 255, 0.15),  
    rgba(255, 255, 255, 0.10),  
    rgba(255, 255, 255, 0.05),  
    transparent                
  );

  -webkit-mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
  -webkit-mask-composite: xor;
  mask-composite: exclude;
  pointer-events: none;
}




/* =====Weather BG Styling===== */
/* Glass Background Effect */
#main {
  background-color: rgba(255, 255, 255, 0.08);
  border-radius: 35px;
  backdrop-filter: blur(25px) saturate(150%);
  -webkit-backdrop-filter: blur(12px) saturate(150%);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  position: relative;
  padding: 18px;
}

/* Shiny Line Effect */
#main::before {
  content: "";
  position: absolute;
  inset: 0;
  border-radius: inherit;
  padding: 1.5px;
  background: linear-gradient(
    to bottom,
    rgba(255, 255, 255, 0.15),  
    rgba(255, 255, 255, 0.10),  
    rgba(255, 255, 255, 0.05),  
    transparent                
  );

  -webkit-mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
  -webkit-mask-composite: xor;
  mask-composite: exclude;
  pointer-events: none;
}



/* =====Analog Clock Styling====== */
/* Glass Background Effect*/
.analog {
  background-color: rgba(255, 255, 255, 0.08);
  backdrop-filter: blur(12px) saturate(150%);
  -webkit-backdrop-filter: blur(12px) saturate(150%);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  position: relative;
	}
	
/* Shiny Line Effect */
.analog::before {
  content: "";
  position: absolute;
  inset: -2.5px;
  border-radius: inherit;
  padding: 1.5px;
  background: linear-gradient(
    to bottom,
    rgba(255, 255, 255, 0.15),  
    rgba(255, 255, 255, 0.10),  
    rgba(255, 255, 255, 0.05),  
    transparent                
  );

  -webkit-mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
  -webkit-mask-composite: xor;
  mask-composite: exclude;
  pointer-events: none;
}
```
</details>

Please keep in mind all of this is solely based of my preferences. This is just my personal repo to use with sine, if you somehow found this repo for whatever reason then idk. You may use this for your (whatever), just be sure to check out and credits the original author I guess...

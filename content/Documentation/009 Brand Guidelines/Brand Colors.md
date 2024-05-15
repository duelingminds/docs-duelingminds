---
title: Brand Colors
publish: true
tags: []
---

## Proposed Palette Revision


<style>
  .color-palette {
    display: flex;
    flex-wrap: wrap;
    width: 80%;
    gap: 10px;
  }
  .color-box {
    width: 100px;
    height: 100px;
    border-radius: 5px;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
  }
  .badge {
    background-color: #4CAF50;
    color: white;
    padding: 6px 12px;
    border-radius: 10px;
  }

  .fail {
    background-color: #FF5722;
    color: white;
    border: 1px;
  }
  .pass {
	background-color: #4CAF50;
	color: black;
	border: 1px;
  }
  .borderline {
	background-color: yellow;
	color: black;
  }
</style>

<div class="color-palette">
  <div class="color-box" style="background-color: #1E262F"></div>
  <div class="color-box" style="background-color: #443355;"></div>
  <div class="color-box" style="background-color: #395252;"></div>
  <div class="color-box" style="background-color: #A6403A;"></div>
  <div class="color-box" style="background-color: #D87550;"></div>
  <div class="color-box" style="background-color: #E8B387;"></div>
  <div class="color-box" style="background-color: #E9D3B9;"></div>
  <div class="color-box" style="background-color: #FEFEF1;"></div>
</div>



## Text Contrast WCAG compliance

| Combination                                                                                 | BG  Color | Text Color | WCAG  | Pass/Fail                                             |
| ------------------------------------------------------------------------------------------- | --------- | ---------- | ----- | ----------------------------------------------------- |
| <span class="badge" style="background-color: #1E262F; color: #FEFEF1;">Dueling Minds</span> | `#1E262F` | `#FEFEF1`  | 15.04 | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #FEFEF1; color: #1E262F;">Dueling Minds</span> | `#FEFEF1` | `#1E262F`  | 15.04 | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #1C3045; color: #FEFEF1;">Dueling Minds</span> | `#1C3045` | `#FEFEF1`  | 13.26 | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #FEFEF1; color: #1C3045;">Dueling Minds</span> | `#FEFEF1` | `#1C3045`  | 13.26 | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #443355; color: #FEFEF1;">Dueling Minds</span> | `#443355` | `#FEFEF1`  | 11.17 | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #FEFEF1; color: #443355;">Dueling Minds</span> | `#FEFEF1` | `#443355`  | 11.17 | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #1E262F; color: #E9D3B9;">Dueling Minds</span> | `#1E262F` | `#E9D3B9`  | 10.54 | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #E9D3B9; color: #1E262F;">Dueling Minds</span> | `#E9D3B9` | `#1E262F`  | 10.54 | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #1C3045; color: #E9D3B9;">Dueling Minds</span> | `#1C3045` | `#E9D3B9`  | 9.30  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #E9D3B9; color: #1C3045;">Dueling Minds</span> | `#E9D3B9` | `#1C3045`  | 9.30  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #1E262F; color: #E8B387;">Dueling Minds</span> | `#1E262F` | `#E8B387`  | 8.18  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #E8B387; color: #1E262F;">Dueling Minds</span> | `#E8B387` | `#1E262F`  | 8.18  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #443355; color: #E9D3B9;">Dueling Minds</span> | `#443355` | `#E9D3B9`  | 7.83  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #E9D3B9; color: #443355;">Dueling Minds</span> | `#E9D3B9` | `#443355`  | 7.83  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #1C3045; color: #FEFEF1;">Dueling Minds</span> | `#1C3045` | `#E8B387`  | 7.21  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #FEFEF1; color: #1C3045;">Dueling Minds</span> | `#E8B387` | `#1C3045`  | 7.21  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #3C6262; color: #FEFEF1;">Dueling Minds</span> | `#3C6262` | `#FEFEF1`  | 6.63  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #FEFEF1; color: #3C6262;">Dueling Minds</span> | `#FEFEF1` | `#3C6262`  | 6.63  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #443355; color: #E8B387;">Dueling Minds</span> | `#443355` | `#E8B387`  | 6.07  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #E8B387; color: #443355;">Dueling Minds</span> | `#E8B387` | `#443355`  | 6.07  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #A6403A; color: #FEFEF1;">Dueling Minds</span> | `#A6403A` | `#FEFEF1`  | 6.05  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #FEFEF1; color: #A6403A;">Dueling Minds</span> | `#FEFEF1` | `#A6403A`  | 6.05  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #1E262F; color: #D87550;">Dueling Minds</span> | `#1E262F` | `#D87550`  | 4.79  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #D87550; color: #1E262F;">Dueling Minds</span> | `#D87550` | `#1E262F`  | 4.79  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #3C6262; color: #E9D3B9;">Dueling Minds</span> | `#3C6262` | `#E9D3B9`  | 4.65  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #E9D3B9; color: #3C6262;">Dueling Minds</span> | `#E9D3B9` | `#3C6262`  | 4.65  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #A6403A; color: #E9D3B9;">Dueling Minds</span> | `#A6403A` | `#E9D3B9`  | 4.24  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #E9D3B9; color: #A6403A;">Dueling Minds</span> | `#E9D3B9` | `#A6403A`  | 4.24  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #1C3045; color: #D87550;">Dueling Minds</span> | `#1C3045` | `#D87550`  | 4.22  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #D87550; color: #1C3045;">Dueling Minds</span> | `#D87550` | `#1C3045`  | 4.22  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #3C6262; color: #E8B387;">Dueling Minds</span> | `#3C6262` | `#E8B387`  | 3.60  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #E8B387; color: #3C6262;">Dueling Minds</span> | `#E8B387` | `#3C6262`  | 3.60  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #443355; color: #D87550;">Dueling Minds</span> | `#443355` | `#D87550`  | 3.56  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #D87550; color: #443355;">Dueling Minds</span> | `#D87550` | `#443355`  | 3.56  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #A6403A; color: #E8B387;">Dueling Minds</span> | `#A6403A` | `#E8B387`  | 3.29  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #E8B387; color: #A6403A;">Dueling Minds</span> | `#E8B387` | `#A6403A`  | 3.29  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #D87550; color: #FEFEF1;">Dueling Minds</span> | `#D87550` | `#FEFEF1`  | 3.14  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #FEFEF1; color: #D87550;">Dueling Minds</span> | `#FEFEF1` | `#D87550`  | 3.14  | <span class="borderline badge">18 or 14pt Bold</span> |


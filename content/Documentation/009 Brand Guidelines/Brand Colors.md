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
    width: 60%;
    margin-left:20%;
    margin-right:20%;
    gap: 10px;
  }
  .color-box {
    display:block;
    flex-basis: calc(33.33% - 10px);
    aspect-ratio: 1;
    border-radius: 5px;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
  }
  .color-pallete .wd-outer {
    width: 100%;
    margin-left: 0;
    margin-right: 0;
  }
  .wd-outer {
    width: 100%;
    margin-left: 0;
    margin-right: 0;
  }
  .wd {
    color: #FEFEF1;
    padding-top: 14%;
    padding-left: 1%;
    padding-right: 1%;
    text-align: center;
    vertical-align: middle;
    line-height: 10%;
  }
  .wd-light {
    color: #1E262F;
    padding-top: 14%;
    padding-left: 1%;
    padding-right: 1%;
    text-align: center;
    vertical-align: middle;
    line-height: 10%;

  }
  .wd-60 {
    flex-basis: calc(30% - 10px);
    aspect-ratio: 2;
  }
  .wd-30 {
    flex-basis: calc(20% - 10px);
    aspect-ratio: 2;
  }
  .wd-10 {
    flex-basis: calc(10% - 10px);
    aspect-ratio: 2;
  }
  .badge {
    display: inline-block;
    text-align: center;
    background-color: #4CAF50;
    color: white;
    padding: 6px 12px;
    border-radius: 10px;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
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
  <div class="color-box" style="background-color: #1E262F;"><center class="badge">#1E262F</center></div>
  <div class="color-box" style="background-color: #443355;"><center class="badge">#443355</center></div>
  <div class="color-box" style="background-color: #1C3045;"><center class="badge">#1C3045</center></div>
  <div class="color-box" style="background-color: #3C6262;"><center class="badge">#3C6262</center></div>
  <div class="color-box" style="background-color: #A6403A;"><center class="badge">#A6403A</center></div>
  <div class="color-box" style="background-color: #D87550;"><center class="badge">#D87550</center></div>
  <div class="color-box" style="background-color: #E9D3B9;"><center class="badge">#E9D3B9</center></div>
  <div class="color-box" style="background-color: #FEFEF1;"><center class="badge">#FEFEF1</center></div>
</div>

## Brand Color Combinations

### Dark Background 1

<div class="color-palette wd-outer">
  <div class="color-box wd wd-60" style="background-color: #1C3045;">Primary</div>
  <div class="color-box wd wd-30" style="background-color: #D87550;">Secondary</div>
  <div class="color-box wd wd-10" style="background-color: #A6403A;">Accent</div>
  <div class="color-box wd wd-10" style="background-color: #1E262F;">Text</div>
  <div class="color-box wd-light wd-10" style="background-color: #FEFEF1;">Text</div>
</div>

### Dark Background 2

<div class="color-palette wd-outer">
  <div class="color-box wd wd-60" style="background-color: #443355;">Primary</div>
  <div class="color-box wd-light wd-30" style="background-color: #E9D3B9;">Secondary</div>
  <div class="color-box wd-light wd-10" style="background-color: #D87550;">Accent</div>
  <div class="color-box wd wd-10" style="background-color: #1E262F;">Text</div>
  <div class="color-box wd-light wd-10" style="background-color: #FEFEF1;">Text</div>
</div>

### Light Background 1

<div class="color-palette wd-outer">
  <div class="color-box wd-light wd-60" style="background-color: #E9D3B9;">Primary</div>
  <div class="color-box wd wd-30" style="background-color: #A6403A;">Secondary</div>
  <div class="color-box wd-light wd-10" style="background-color: #D87550;">Accent</div>
  <div class="color-box wd wd-10" style="background-color: #1E262F;">Text</div>
  <div class="color-box wd-light wd-10" style="background-color: #FEFEF1;">Text</div>
</div>

### Light Background 2

<div class="color-palette wd-outer">
  <div class="color-box wd-light wd-60" style="background-color: #E9D3B9;">Primary</div>
  <div class="color-box wd-light wd-30" style="background-color: #FEFEF1;">Secondary</div>
  <div class="color-box wd wd-10" style="background-color: #A6403A;">Accent</div>
  <div class="color-box wd wd-10" style="background-color: #1E262F;">Text</div>
  <div class="color-box wd-light wd-10" style="background-color: #FEFEF1;">Text</div>
</div>

### Alternate / Spot colors
<div class="color-palette wd-outer">
  <div class="color-box wd wd-10" style="background-color: #3C6262;">Accent</div>
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
| <span class="badge" style="background-color: #443355; color: #E9D3B9;">Dueling Minds</span> | `#443355` | `#E9D3B9`  | 7.83  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #E9D3B9; color: #443355;">Dueling Minds</span> | `#E9D3B9` | `#443355`  | 7.83  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #FEFEF1; color: #1C3045;">Dueling Minds</span> | `#E8B387` | `#1C3045`  | 7.21  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #3C6262; color: #FEFEF1;">Dueling Minds</span> | `#3C6262` | `#FEFEF1`  | 6.63  | <span class="pass badge">Pass</span>                  |
| <span class="badge" style="background-color: #FEFEF1; color: #3C6262;">Dueling Minds</span> | `#FEFEF1` | `#3C6262`  | 6.63  | <span class="pass badge">Pass</span>                  |
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
| <span class="badge" style="background-color: #443355; color: #D87550;">Dueling Minds</span> | `#443355` | `#D87550`  | 3.56  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #D87550; color: #443355;">Dueling Minds</span> | `#D87550` | `#443355`  | 3.56  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #D87550; color: #FEFEF1;">Dueling Minds</span> | `#D87550` | `#FEFEF1`  | 3.14  | <span class="borderline badge">18 or 14pt Bold</span> |
| <span class="badge" style="background-color: #FEFEF1; color: #D87550;">Dueling Minds</span> | `#FEFEF1` | `#D87550`  | 3.14  | <span class="borderline badge">18 or 14pt Bold</span> |


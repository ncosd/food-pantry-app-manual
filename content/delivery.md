---
title: "Delivery"
date: 2023-02-27T11:24:49-05:00
draft: false
---

<div class="p-2 text-bg-info">If you aren't logged in, sends you to the login page.</div>
<div class="p-2 text-bg-info">If you aren't approved for delivery, shows you your status here.</div>
<div class="mb-3 p-2 text-bg-info">If you are approved, shows you your preferences.</div>

## Address
Street 1

Street 2

City, State, Zip

<div class="row">
  <div class="col">
    <label for="num9" class="form-label">Number 0-9</label>
    <input type="text" id="num9" class="form-control">
  </div>
  <div class="col">
    <label for="num1017" class="form-label">Number 10-17</label>
    <input type="text" id="num1017" class="form-control">
  </div>
  <div class="col">
    <label for="num18" class="form-label">Number 18-59</label>
    <input type="text" id="num18" class="form-control">
  </div>
  <div class="col">
    <label for="num60" class="form-label">Number 60+</label>
    <input type="text" id="num60" class="form-control">
  </div>
</div>


<div class="form-check">
  <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault">
  <label class="form-check-label" for="flexCheckDefault">
    On hold
  </label>
</div>

## Preferences
<div class="form-check">
  <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault">
  <label class="form-check-label" for="flexCheckDefault">
    Vegetarian
  </label>
</div>

<div class="form-check">
  <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault">
  <label class="form-check-label" for="flexCheckDefault">
    Allergies
  </label>
    <label for="exampleAllergies" class="form-label">List Allergies</label>
    <input type="text" class="form-control" id="exampleAllergies" aria-describedby="allergyHelp" value="nuts, dairy">
    <div id="allergyHelp" class="form-text">List of things you cannot consume</div>
</div>



## Next delivery
DayofWeek Month Day, Year

---
layout: page
title: Registration
---
<div class="col-lg-12 text-center">
	<h2 class="section-heading text-uppercase">{{ page.title }}</h2>
</div>
<br>

Registration for **GandALF 2026** is available in two options:

| Registration Type     | Period                        |           Fee |
| --------------------- | ----------------------------- | ------------: |
| **Early**             | Until **20 August 2026**      | **3,200 DKK** |
| **Regular**           | From **21 August 2026**       | **3,800 DKK** |

Both registration options include:

* Admission to the conference on **15–17 September 2026**;
* Lunch on all conference days;
* Coffee breaks;
* Participation in the conference social activities.

We encourage participants to take advantage of the **Early Registration** rate by registering before **20 August 2026**.

<div class="registration_container">
<div class="container">
    <h2 id="registrationStatus" style="text-align: center; margin-top: 0; margin-bottom: 20px;"></h2>
    <form id="registrationForm">
      
      <div class="row" style="margin-bottom: 18px;">
        <div class="form-group">
          <label for="name">Name <span class="required-asterisk">*</span></label>
          <input type="text" id="name" placeholder="John" required>
        </div>
        <div class="form-group">
          <label for="surname">Surname <span class="required-asterisk">*</span></label>
          <input type="text" id="surname" placeholder="Smith" required>
        </div>
      </div>

      <div class="form-group">
        <label for="email">Email <span class="required-asterisk">*</span></label>
        <input type="email" id="email" placeholder="jsmith@cs.aau.dk" required>
      </div>

      <div class="form-group">
        <label for="affiliation">Affiliation <span class="required-asterisk">*</span></label>
        <input type="text" id="affiliation" placeholder="Aalborg University, DK" required>
      </div>

      <fieldset class="fieldset">
        <legend>Billing Address</legend>
        <div class="form-group">
          <label for="address">Address <span class="required-asterisk">*</span></label>
          <input type="text" id="address" placeholder="Selma Lagerløfs Vej 300" required>
        </div>
        
        <div class="row">
          <div class="form-group">
            <label for="postCode">Postal Code <span class="required-asterisk">*</span></label>
            <input type="text" id="postCode" placeholder="9220" required>
          </div>
          <div class="form-group">
            <label for="city">City <span class="required-asterisk">*</span></label>
            <input type="text" id="city" placeholder="Aalborg East" required>
          </div>
        </div>

        <div class="form-group" style="margin-top: 15px;">
          <label for="country">Country <span class="required-asterisk">*</span></label>
          <input type="text" id="country" placeholder="Denmark" required>
        </div>
      </fieldset>

      <fieldset class="fieldset">
        <legend>Extra guests at the social dinner (max 5)</legend>
        <div class="form-group">
          <label for="guests">Number of guests (+780 DKK/guest):</label>
          <input type="number" id="guests" name="guests" min="0" max="5" value="0">
      </div>
      </fieldset>

      <div class="form-group">
        <label for="dietary">Dietary requirements (Optional)</label>
        <textarea id="dietary" rows="3" placeholder="Please list any allergies or dietary restrictions (including guests)..."></textarea>
      </div>

      <div class="checkbox-group">
        <input type="checkbox" id="invoice" >
        <label for="invoice">I want to receive printed copy of the invoice at registration desk (Optional)</label>
      </div>

      <div class="checkbox-group">
        <input type="checkbox" id="terms" required>
        <label for="terms"><span class="required-asterisk">*</span>I confirm that the above data is correct and that I agree to the terms of the <a href="https://gandalfsymposium.github.io/2026/legal" target="_blank">Privacy Policy, and Registration Conditions</a> of GandALF 2026.</label>
      </div>

      <div class="form-group" style="margin-top: 30px;">
        <!-- Button is disabled by default -->
        <button type="submit" id="checkoutBtn" class="submit-btn" disabled>Checkout</button>
      </div>
      
      <div id="loadingMsg">Securely processing your registration...</div>
    </form>
  </div>
  </div>

---
layout: page
title: Quiz
description: Should you become a dentist?
background: '/img/bg-quiz.jpg'
---

Take this quiz to see if you should consider becoming a dentist. Please note this is just for fun and not based on official sources.

<form onsubmit="quiz_form_handle(); return false;">
    <h3>Are you a good communicator?</h3>
    <label>
        <input type="radio" name="q1" data-choice="yes" required>
        Yes
    </label> <br>
    <label>
        <input type="radio" name="q1" data-choice="sometimes">
        Sometimes
    </label> <br>
    <label>
        <input type="radio" name="q1" data-choice="no">
        no
    </label> <br> <br>
    <h3>Do you enjoy providing care for others?</h3>
    <label>
        <input type="radio" name="q2" data-choice="yes" required>
        Yes
    </label> <br>
    <label>
        <input type="radio" name="q2" data-choice="sometimes">
        Sometimes
    </label> <br>
    <label>
        <input type="radio" name="q2" data-choice="no">
        no
    </label> <br> <br>
    <h3>Do you work well under pressure?</h3>
    <label>
        <input type="radio" name="q3" data-choice="yes" required>
        Yes
    </label> <br>
    <label>
        <input type="radio" name="q3" data-choice="sometimes">
        Sometimes
    </label> <br>
    <label>
        <input type="radio" name="q3" data-choice="No">
        No
    </label> <br> <br>
    <h3>Are you committed to constantly learning new things as new dental techniques are being created?</h3>
    <label>
        <input type="radio" name="q4" data-choice="yes" required>
        Yes
    </label> <br>
    <label>
        <input type="radio" name="q4" data-choice="sometimes">
        Sometimes
    </label> <br>
    <label>
        <input type="radio" name="q4" data-choice="No">
        No
    </label> <br> <br>
    <h3>Do you like science?</h3>
    <label>
        <input type="radio" name="q5" data-choice="yes" required>
        Yes
    </label> <br>
    <label>
        <input type="radio" name="q5" data-choice="sometimes">
        Sometimes
    </label> <br>
    <label>
        <input type="radio" name="q5" data-choice="No">
        No
    </label> <br> <br>
    <button type="button submit" class="btn btn-dark">Submit</button> <br> <br>
</form>
<h1 id="result" style="display: none;">text</h1>
<script>
    //
    function quiz_form_handle() {
        //
        let total = 0;
        const q1_result = document.querySelector('input[name="q1"]:checked').getAttribute('data-choice');
        const q2_result = document.querySelector('input[name="q2"]:checked').getAttribute('data-choice');
        const q3_result = document.querySelector('input[name="q3"]:checked').getAttribute('data-choice');
        const q4_result = document.querySelector('input[name="q4"]:checked').getAttribute('data-choice');
        const q5_result = document.querySelector('input[name="q5"]:checked').getAttribute('data-choice');
        const result_element = document.getElementById("result");
        if(q1_result==="yes") {
            total += 5;
        }
        if(q1_result==="sometimes") {
            total += 2;
        }
        if(q1_result==="no") {
            total += 0;
        }
        if(q2_result==="yes") {
            total += 5;
        }
        if(q2_result==="sometimes") {
            total += 2;
        }
        if(q2_result==="no") {
            total += 0;
        }
        if(q3_result==="yes") {
            total += 5;
        }
        if(q3_result==="sometimes") {
            total += 2;
        }
        if(q3_result==="no") {
            total += 0;
        }
        if(q4_result==="yes") {
            total += 5;
        }
        if(q4_result==="sometimes") {
            total += 2;
        }
        if(q4_result==="no") {
            total += 0;
        }
        if(q5_result==="yes") {
            total += 5;
        }
        if(q5_result==="sometimes") {
            total += 2;
        }
        if(q5_result==="no") {
            total += 0;
        }
        if(total < 12) {
            result_element.innerText = "Result: You should probably NOT go into dentistry.";
        }
        if(total >= 12 && total <= 18) {
            result_element.innerText = "Result: You should MAYBE go into dentistry.";
        }
        if(total > 18) {
            result_element.innerText = "Result: You should PROBABLY go into dentistry.";
        }
        result_element.style.display = "block";
    }
</script>
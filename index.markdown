---
layout: home
background: '/img/mouth.jpg'
---

Dentistry is a branch of medicine that deals with teeth, gums and the mouth and has been around since the ancient Egyptians (7500 BC).  Dentistry uses technology to provide better patient care and is constantly changing as new advances are being made. This site will examine dental innovations of the past and possible future. Below you can find some important events in Dental History!

<div class="timeline">
    <div class="timeline-container left-timeline-container">
        <i class="bi bi-circle-fill timeline-icon"></i>
        <div class="text-box">
            <h2>2600BC</h2>
            <p1>Hesy-Ra was an ancient Egyptian scribe credited as being the first known dentist after treating tooth infenctions.</p1>
            <img src="img/timeline/2600BC.jpg" class="img-thumbnail">
            <span class="left-container-arrow"></span>
        </div>
    </div>
    <div class="timeline-container right-timeline-container">
        <i class="bi bi-circle-fill timeline-icon"></i>
        <div class="text-box">
            <h2>1723</h2>
            <p1>Pierre Fauchard published a book called "The Surgeon Dentist, a Treatise on Teeth" which was the first source on specific dental care. He became credited as the Father of Modern Dentistry.</p1>
            <img src="img/timeline/1723.jpg" class="img-thumbnail">
            <span class="right-container-arrow"></span>
        </div>
    </div>
    <div class="timeline-container left-timeline-container">
        <i class="bi bi-circle-fill timeline-icon"></i>
        <div class="text-box">
            <h2>1840</h2>
            <p1>Baltimore College of Dental Surgery opened and became the first dental school.</p1>
            <img src="img/timeline/1840.jpg" class="img-thumbnail">
            <span class="left-container-arrow"></span>
        </div>
    </div>
    <div class="timeline-container right-timeline-container">
        <i class="bi bi-circle-fill timeline-icon"></i>
        <div class="text-box">
            <h2>1873</h2>
            <p1>Colgate began to mass produce toothpaste.</p1>
            <img src="img/timeline/1873.jpg" class="img-thumbnail">
            <span class="right-container-arrow"></span>
        </div>
    </div>
    <div class="timeline-container left-timeline-container">
        <i class="bi bi-circle-fill timeline-icon"></i>
        <div class="text-box">
            <h2>1896</h2>
            <p1>Dr Otto Walkhoff created the first dental x-ray.</p1>
            <img src="img/timeline/1896.jpg" class="img-thumbnail">
            <span class="left-container-arrow"></span>
        </div>
    </div>
    <div class="timeline-container right-timeline-container">
        <i class="bi bi-circle-fill timeline-icon"></i>
        <div class="text-box">
            <h2>1911</h2>
            <p1>The U.S. Army Dental Corps is created.</p1>
            <img src="img/timeline/1911.jpg" class="img-thumbnail">
            <span class="right-container-arrow"></span>
        </div>
    </div>
    <div class="timeline-container left-timeline-container">
        <i class="bi bi-circle-fill timeline-icon"></i>
        <div class="text-box">
            <h2>1913</h2>
            <p1>Fones Clinic For Dental Hygienists in Bridgeport, Connecticut became the world's first school for dental hygienists.</p1>
            <img src="img/timeline/1913.jpg" class="img-thumbnail">
            <span class="left-container-arrow"></span>
        </div>
    </div>
    <div class="timeline-container right-timeline-container">
        <i class="bi bi-circle-fill timeline-icon"></i>
        <div class="text-box">
            <h2>1930</h2>
            <p1>The American Board of Orthodontics was created and became the first dental specialty.</p1>
            <img src="img/timeline/1930.jpg" class="img-thumbnail">
            <span class="right-container-arrow"></span>
        </div>
    </div>
    <div class="timeline-container left-timeline-container">
        <i class="bi bi-circle-fill timeline-icon"></i>
        <div class="text-box">
            <h2>1957</h2>
            <p1>John Borden created a modern high speed dental drill which spined at a speed of 300,000 RPM.</p1>
            <img src="img/timeline/1957.jpg" class="img-thumbnail">
            <span class="left-container-arrow"></span>
        </div>
    </div>
    <div class="timeline-container right-timeline-container">
        <i class="bi bi-circle-fill timeline-icon"></i>
        <div class="text-box">
            <h2>1960</h2>
            <p1>It became common practice for a dentist and dental assistant to work together during a patient visit. This made treatments faster and more efficent.</p1>
            <img src="img/timeline/1960.jpg" class="img-thumbnail">
            <span class="right-container-arrow"></span>
        </div>
    </div>
</div>
<style>
.img-thumbnail {
    border: none;
    padding: 0px;
}

.timeline {
    position: relative;
    max-width: 1200px;
    margin: 100px auto;
}

.timeline-container {
    padding: 10px 50px;
    position: relative;
    width: 50%;
}

.text-box {
    padding: 20px 30px;
    background: white;
    border: 5px solid black;
    position: relative;
    border-radius: 6px;
    font-size: 15px;
}

.left-timeline-container {
    left: 0;
}

.right-timeline-container {
    left: 50%;
}

.timeline-icon {
    position: absolute;
    width: 40px;
    border-radius: 50%;
    right: -20px;
    top: 32px;
    z-index: 10;
}

.right-timeline-container .timeline-icon {
    left: -20px;
}

.timeline::after {
    content: '';
    position: absolute;
    width: 6px;
    background-color: black;
    top: 0;
    bottom: 0;
    left: 50%;
    margin-top: 10px;
    margin-left: -15px;
}

.text-box h2 {
    font-weight: 600;
}

.text-box small {
    display: inline-block;
    margin-bottom: 15px;
}

.left-container-arrow {
    height: 0;
    width: 0;
    position: absolute;
    top: 20px;
    z-index: 1;
    border-top: 15px solid transparent;
    border-bottom: 15px solid transparent;
    border-left: 15px solid black;
    right: -15px;
}

.right-container-arrow {
    height: 0;
    width: 0;
    position: absolute;
    top: 20px;
    z-index: 1;
    border-top: 15px solid transparent;
    border-bottom: 15px solid transparent;
    border-right: 15px solid black;
    left: -15px;
}

@media screen and (max-width: 600px) {
    .timeline {
        margin: 50px auto;
    }
    .timeline::after {
        left: 31px;
    }
    .timeline-container {
        width: 100%;
        padding-left: 80px;
        padding-right: 25px;
    }
    .text-box {
        font-size: 13px;
    }
    .text-box small {
        margin-bottom: 10px;
    }
    .right-timeline-container {
        left: 0;
    }
    .timeline-icon {
        left: 10px;
    }
    .left-container-arrow, .right-container-arrow {
        border-right: 15px solid black;
        border-left: 0;
        left: -15px;
    }
}

</style>
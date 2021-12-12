<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Technical Aayushji</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet"> 
    <link rel="stylesheet" href="blog.css" />

</head>
<body>
    <div class="header">
        <h2> HI! WELLCOME Back TO POULAMIS BLOG</h2>
    </div>

    <div class="container">
        <div class="leftcontent">
            <div class="card">
                <h4>MALDIVES STORY</h4>
                <img src="im4.jpg"/>
                <p>  At Experience Travel Group, we hope to help travellers unlock the true magic of the Maldives. Our experts know where to find the best of the best hotels, and what makes each one unique too (we all know that they can all look pretty similar online!). However, we’re also passionate about taking you beyond the beaches and the marine life, and diving into an all-too-often overlooked aspect: the local culture. We can combine your luxury Maldives holiday with an insight into true Maldivian life, whether it’s tasting authentic street food or hopping aboard a local fishing boat. You may also wish to combine the Maldives with Sri Lanka, or another South Asian country; we’d love to help with that too    </p>
            </div>

            <div class="card">
                <h4>MALDIVES DETAILS</h4>
                <img src="img5.jpg"/>
                <p> Christmas came early a few years ago as luxury expert Matt got to stay at both the Four Seasons in the Maldives – Kudaa Hura and Landaa Giravaaru, and Song Saa Private Island off the southern coast of Cambodia.

                    Sustainable TravelThe Maldives
                    WHAT ‘SUSTAINABILITY’ MEANS IN THE MALDIVES
                    Sustainability in the Maldives can be hard to quantify. Our Head of Responsible Travel, Alice Bayly, takes a deep dive into what sustainability in the Maldives really means.
                    
                     </p>
            </div>
        </div>
        <div class="rightcontent">
            <div class="card">
                <h4>About me</h4>
                <img />
                <p>Some good stuff about me.</p>
            </div>
            <div class="card right-sticky">
                <h5>Sections</h5>
                <ul>
                    <li>Programming</li>
                    <li>Travel</li>
                    <li>Food</li>
                    <li>Health & Fitness</li>
                    <li>Music & Lifestyle</li>
                </ul>
            </div>
        </div>
    </div>
  <style>
    
    body {
    background-color: #9A9A9A;
    margin: 0px;
}

h2 {
    font-family: 'Roboto', sans-serif;
}

h2, h4 {
    margin: 0px;
}

.header, .card {
    background-color: #FFFFFF;
    padding: 30px;
    font-size: 40px;
    text-align: center;

}

.header {
    position: sticky;
    top: 0px;
}

.container {
    display: flex;
}

.leftcontent {
    padding: 5px;
    width: calc(70% - 10px);
    float: left;
}

.rightcontent {
    padding: 5px;
    width: calc(30% - 10px);
    float: right;
}

.card {
    margin: 5px 0px;
    padding: 10px;
    background-color: #FFFFFF;
}

img {
    width: 100%;
}

.right-sticky {
    position: sticky;
    top: 40px;
}
</style>
 <script src="blog.js"></script>
</body>
</html>

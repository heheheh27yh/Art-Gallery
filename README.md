<!DOCTYPE html>
<html lang="en">
<head>
    <title>Art Gallery</title>
    <style>
        body {
            font-family:'Times New Roman','Times New Roman'  ;
            margin: 0;
            padding: 0;
            background-color: #c8f1f7;
            color: #333;
        }
        header {
            background-color: #05142f;
            color: #f4f9fc;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .gallery {
            display: flex;  
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .gallery-item {
            margin: 15px;
            width: 300px;
            background-color: #bdc7db;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .gallery-item:hover {
            transform: scale(1.05);
        }
        .gallery-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .gallery-item .description {
            padding: 15px;
            text-align: center;
        }
        .gallery-item .description h3 {
            margin: 0 0 10px;
            font-size: 1.2em;
        }
        .gallery-item .description p {
            margin: 0;
            font-size: 0.9em;
            color: #666;
        }
        footer {
            background-color: #242121;
            color: #c8eaca;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Art Gallery</h1>
    </header>
<section class="gallery">
        <div class="gallery-item">
            <img src="https://thepopularlist.com/wp-content/uploads/2020/07/800px-Hovhannes_Aivazovsky_-_The_Ninth_
            Wave_-_Google_Art_Project.jpg" alt="Art 1">
            <div class="description">
                <h3>The Ninth Wave By Ivan Aivazovsky</h3>
                <p> This painting is the perfect example of a storm both in terms of the weather depiction and emotions.
                     It is believed that the ninth shaft is the strongest of the waves, and nothing can withstand its power.
</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="https://anitalouiseart.com/wp-content/uploads/2023/04/Starry-Night-1889-By-Vincent-van-Gogh.
            jpeg?ezimgfmt=ng:webp/ngcb11" alt="Art 2">
            <div class="description">
                <h3>The Starry Night (Vincent van Gogh, 1889)
                </h3>
                <p>Vincent van Gogh’s swirling skies and bold use of color and brushwork have made “The Starry Night” 
                    a favorite subject for academic studies and dorm room posters. The painting captures both the beauty 
                    of the night sky and the anguish of van Gogh’s mental turmoil.</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="https://thepopularlist.com/wp-content/uploads/2020/07/Turner_J._M._W._-_The_Grand_Canal_-_Venice-1.jpg" alt="Art 3">
            <div class="description">
                <h3> The Grand Canal, Venice By JMW Turner</h3>
                <p>J.M.W. Turner painted The Grand Canal, Venice, on his second visit to the city. This painting was a part 
                    of the series the painter made showing the city in different views, capturing stunning scenes through his 
                    dynamic lens of romance and sensibility. The artist was known for his incredible knowledge of using colors
                     and dramatic light to portray nature beautifully.
</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="https://thepopularlist.com/wp-content/uploads/2020/07/1024px-Winslow_Homer_-_Breezing_Up_A_Fair_Wind_-_Google
            _Art_Project.jpg" alt="Art 4">
            <div class="description">
                <h3>Breezing Up By Winslow Homer</h3>
                <p>Winslow Homer is popular for developing an inclination towards realism right from the start of his career. T
                    he Breezing Up (A Fair Wind) was completed during the centennial of the country and became the most beloved
                     and well-known artistic work in America.</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="https://thepopularlist.com/wp-content/uploads/2019/11/The-Embarkation-of-the-Queen-of-Sheba-by-Claude-
            Lorrain.jpg" alt="Art 4">
            <div class="description">
                <h3> The Embarkation Of The Queen Of Sheba By Claude Lorrain</h3>
                <p>The Embarkation Of The Queen of Sheba by Claude Lorrain was made in the year 1648 and features Queen Sheba 
                    making a visit to Jerusalem to meet King Solomon. This is a common Biblical scene made memorable due to the 
                    significance of the event as well as the beautiful classical buildings in its surroundings.</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="https://thepopularlist.com/wp-content/uploads/2019/11/Nighthawks-by-Edward-Hopper.jpg" alt="Art 4">
            <div class="description">
                <h3> Nighthawks By Edward Hopper</h3>
                <p>This painting was made in the year 1942 and features four modern characters at a diner engaged in different activities. 
                    It is one of the best depictions of the isolation that people experience in a modern urban setting.</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="https://thepopularlist.com/wp-content/uploads/2019/11/Rain%E2%80%99s-Rustle-by-Leonid-Afremov.jpg" alt="Art 4">
            <div class="description">
                <h3> Rain’s Rustle By Leonid Afremov</h3>
                <p>Rain’s Rustle is a popular and famous painting by Israeli painter Leonid Afremov and features a burst of color in oil 
                    paint on canvas. The artist was famous for cityscapes that featured rain and lighting.</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="https://thepopularlist.com/wp-content/uploads/2019/11/Kanagawa-by-Hokusai.jpg" alt="Art 4">
            <div class="description">
                <h3> The Great Wave Of Kanagawa By Hokusai</h3>
                <p>Hokusai may not be as well known as many western painters, but he has been an inspiration for many of the most famous 
                    painters we know today. He produced a series of prints of Mount Fuji which made him famous the world over.</p>
        </div>
        </section>

</body>
</html>

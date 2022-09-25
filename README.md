<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="ParallaxWeb.css">
    <title>Parallax Effect Website Page..!</title>
</head>

<body id="budy" bgcolor="gray">
    <div id="container">
        <div id="contraster">
            <h3> Web Prototype </h3>
            <h5>This is only Responsive WEB Prototype..Therefore There Have No
                BackEnd, Database Developing.WORK IN PROGRESS...
                <br>
                <hr id="hrclr">
                <br>
                <button id="btun_02">Click Here Hidden Content</button>
                <br>
                <br>

                <h5 id="hdncnt">"Hidden Content" Here !
                    <br><br>
                    <button id="btun_03">Click Here To Open Google Link</button>
                </h5>
                <hr id="hrclr">
                <br>

            </h5>

        </div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum, eaque cum temporibus eveniet fuga veritatis
            animi quibusdam velit tempora nostrum assumenda illo doloremque provident laboriosam nesciunt recusandae
            dolorem voluptas cupiditate consequatur? Soluta mollitia suscipit enim, cupiditate debitis, ipsa quidem
            nihil voluptate eius temporibus beatae? Saepe, quia iure molestias corporis eos aliquam tempora inventore
            ab? Odio ullam, eaque labore voluptates pariatur excepturi non ea, sed culpa dolor dignissimos. Tempora
            esse, rem quia corporis magni enim, ipsam sapiente veniam magnam odit fugit earum culpa, dolor nisi
            dignissimos a architecto. Magni, voluptatem. Nisi itaque ratione numquam vitae eum molestias. Corporis,
            laborum asperiores nisi delectus iure quaerat, harum, voluptates aspernatur autem ea culpa vero obcaecati
            optio? Iste quas, natus neque architecto dolore itaque dignissimos eaque! Nulla quasi blanditiis perferendis
            excepturi ut? Ea, at iure provident deserunt sed, error praesentium officiis dicta, dignissimos alias fumer.
        </p>
        <div class="parallax">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis nobis distinctio aut eius molestiae ex
                dolore voluptatibus incidunt
                quos laudantium.</p>
        </div>

        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem aliquam necessitatibus blanditiis dicta sit.
            Esse velit consequatur animi, officia non eligendi delectus quasi natus commodi omnis unde aliquid.
            Perspiciatis earum aperiam reprehenderit illum dolorem est doloremque fugiat, totam doloribus aspernatur
            nihil laborum impedit explicabo aliquid autem rem corporis quis alias, facere harum repellendus recusandae
            repellat possimus qui. Earum autem id aut rem aliquid inventore dolores ut at ipsam commodi ratione quidem
            pariatur consectetur incidunt, corporis possimus repudiandae ea dignissimos facere sunt modi asperiores eos
            iste. Earum corrupti id blanditiis, architecto ipsam quod est a tempore, at voluptates ad magni magnam
            officiis unde, cum nisi harum? Quasi, facilis autem. Magnam quae, asperiores voluptatum similique amet iste
            officia molestias omnis totam placeat culpa explicabo beatae quis deleniti quod nam rem. Aliquam, iusto quis
            iure similique, cumque recusandae soluta dignissimos, vero placeat rem deleniti quo saepe neque non
            veritatis? Hic perspiciatis, officia laboriosam ad quod possimus minus ipsum omnis excepturi assumenda
            accusantium dolore aliquam autem iste quidem unde rem deleniti distinctio quisquam accusamus similique. Non
            illo nemo corporis sit eius laborum optio inventore atque delectus vel architecto porro eligendi possimus
            quasi molestias dolore neque corrupti, labore ea numquam exercitationem quam ipsa. Explicabo laboriosam, et
            rem id non dolore dolores unde perferendis ipsum dolorem qui ducimus facere necessitatibus tenetur ipsam
            magni commodi amet. Nesciunt consectetur atque minus provident illum ex commodi, dicta corrupti pariatur nam
            perferendis tenetur, delectus, nulla fugit praesentium libero veritatis labore.</p>

        <div>
            <hr>
            <h4>DEVELOPED BY: Taha <sup> 47 </sup> </h4>
            <br>
            <button id="btn_01">Allowed To Dark Theme</button>
            <hr>
            <br>
        </div>
    </div>

    <script defer>

        var x = document.getElementById('btn_01')
        var bdy = document.getElementById('container')

        var buttonz = document.getElementById('btun_02')
        var buttony = document.getElementById('btun_03')
        var hidden = document.getElementById('hdncnt')

        x.addEventListener('click', function () {
            bdy.style.backgroundColor = 'black';
            bdy.style.color = "snow";



        });

        buttonz.addEventListener('click', function run() {
            hidden.style.display = 'block'
            
        });

        buttony.addEventListener('click', function run() {
            bdy.style.color = 'snow';
        });

    </script>
</body>

</html>

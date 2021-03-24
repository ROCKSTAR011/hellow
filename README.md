
<html>
    <head>
        <title>CARD SELECTION</title>
        <style>
            body{
                background: rgb(157, 60, 160);
            }
            .container{
                width: 100%;
                height: 100%;
            }
            .box{
                margin: 40px;
                display: flex;
                position: relative;
                flex-wrap: wrap;
                align-items: center;
                justify-content: center;
            }
            .box .card{
                margin: 40px;
                padding: 10px;
                text-align: center;
                width: 200px;
                height: 320px;
                background: #fff;
                border-radius: 10px;
                border: 5PX solid red;
                border-inline: 3px solid rgb(255, 196, 0);
                border-bottom: 3px solid rgb(0, 22, 150);
                box-shadow: 0 0 0 0 rgba(3, 56, 189, 0.7);
                animation: peffect 1.72s infinite cubic-bezier(0.66, 0, 0, 1);
                }
                .table{
                    border: 1px solid forestgreen;
                    border-radius: 3px;
                }
                @keyframes peffect {
                to{
                    box-shadow: 0 0 0 30px rgb(255, 249, 230, 0);
                }
            }
        </style>
    </head>
    <body>

        <section class="container">

            <div class="box">

                <div class="card">HELLO <hr>

                    <table border="5" class="table" align="center">
                        <tr>
                            <th class="table">HELLO</th>
                            <th class="table">HOW</th>
                            <th class="table">ARE</th>
                            <th class="table">YOU</th>
                        </tr>
                        <tr>
                            <td colspan="2">I AM R</td>
                            <td>WHO</td>
                            <td>YOU?</td>
                        </tr>
                        <tr>
                            <td colspan="2">I AM R</td>
                            <td>WHO</td>
                            <td>YOU?</td>
                        </tr>
                        <tr>
                            <td colspan="2">I AM R</td>
                            <td>WHO</td>
                            <td>YOU?</td>
                        </tr>
                    </table>

                    <hr>

                    <table border="5" class="table" align="center">
                        <tr>
                            <th class="table">HELLO</th>
                            <th class="table">HOW</th>
                            <th class="table">ARE</th>
                            <th class="table">YOU</th>
                        </tr>
                        <tr>
                            <td colspan="2">I AM R</td>
                            <td>WHO</td>
                            <td>YOU?</td>
                        </tr>
                        <tr>
                            <td colspan="2">I AM R</td>
                            <td>WHO</td>
                            <td>YOU?</td>
                        </tr>
                        <tr>
                            <td colspan="2">I AM R</td>
                            <td>WHO</td>
                            <td>YOU?</td>
                        </tr>
                    </table>

                </div>

                <div class="card">HOW <hr> </div>

                <div class="card">ARE <hr> </div>

                <div class="card">YOU <hr> </div>

                <div class="card">AND <hr> </div>

                <div class="card">YOU <hr> </div>

            </div>
        </section>
    </body>
</html>

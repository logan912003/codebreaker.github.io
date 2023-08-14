# codebreaker.github.io

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Code Breaker</title>
    <link rel="stylesheet" href="codebreaker.css">
    <style>
        .table-container {
            display: flex;
            justify-content: space-between;
            margin: 20px auto;
        }

        table {
            border-collapse: collapse;
            width: 40%;
        }

        th, td {
            border: 1px solid #ccc;
            padding: 8px;
            text-align: center;
        }

        th {
            background-color: #000000;
            color: #00ff00;
        }
    </style>
</head>
<body>
    <div class="center-container">
        <h1>Code Breaker</h1>
        <h2>Directions: Enter the code with dashes in between each number</h2>
        <textarea id="inputCode" placeholder="Enter your code here. Ex: 3-15-4-5..."></textarea>
        <button class=button glitch onclick="generateMessage()">Generate Message</button>
        <p id="outputMessage"></p>
    </div>
    
    <div class="table-container">
        <table>
            <thead>
                <tr>
                    <th>Code</th>
                    <th>Letter</th>
                </tr>
            </thead>
            <tbody>
                <!-- Table 1 - Letters a to m -->
                <tr>
                    <td>1</td>
                    <td>a</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>b</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>c</td>
                </tr>
                <tr>
                    <td>4</td>
                    <td>d</td>
                </tr>
                <tr>
                    <td>5</td>
                    <td>e</td>
                </tr>
                <tr>
                    <td>6</td>
                    <td>f</td>
                </tr>
                <tr>
                    <td>7</td>
                    <td>g</td>
                </tr>
                <tr>
                    <td>8</td>
                    <td>h</td>
                </tr>
                <tr>
                    <td>9</td>
                    <td>i</td>
                </tr>
                <tr>
                    <td>10</td>
                    <td>j</td>
                </tr>
                <tr>
                    <td>11</td>
                    <td>k</td>
                </tr>
                <tr>
                    <td>12</td>
                    <td>l</td>
                </tr>
                <tr>
                    <td>13</td>
                    <td>m</td>
                </tr>
            </tbody>
        </table>
        <table>
            <thead>
                <tr>
                    <th>Code</th>
                    <th>Letter</th>
                </tr>
            </thead>
            <tbody>
                <!-- Table 2 - Letters n to z -->
                <tr>
                    <td>14</td>
                    <td>n</td>
                </tr>
                <tr>
                    <td>15</td>
                    <td>o</td>
                </tr>
                <tr>
                    <td>16</td>
                    <td>p</td>
                </tr>
                <tr>
                    <td>17</td>
                    <td>q</td>
                </tr>
                <tr>
                    <td>18</td>
                    <td>r</td>
                </tr>
                <tr>
                    <td>19</td>
                    <td>s</td>
                </tr>
                <tr>
                    <td>20</td>
                    <td>t</td>
                </tr>
                <tr>
                    <td>21</td>
                    <td>u</td>
                </tr>
                <tr>
                    <td>22</td>
                    <td>v</td>
                </tr>
                <tr>
                    <td>23</td>
                    <td>w</td>
                </tr>
                <tr>
                    <td>24</td>
                    <td>x</td>
                </tr>
                <tr>
                    <td>25</td>
                    <td>y</td>
                </tr>
                <tr>
                    <td>26</td>
                    <td>z</td>
                </tr>
            </tbody>
        </table>
    </div>

    <script src="codebreaker.js"></script>
</body>
</html>

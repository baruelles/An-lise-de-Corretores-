<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Análise de Corretores</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1, h2 {
            text-align: center;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        .chart {
            width: 100%;
            display: flex;
            justify-content: center;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <h1>Análise de Corretores</h1>
    
    <h2>Dados Brutos</h2>
    <table>
        <tr>
            <th>Corretor</th>
            <th>Captações</th>
            <th>Atendimentos</th>
            <th>Visitas</th>
        </tr>
        <tr>
            <td>Aleandra Pereira dos Santos</td>
            <td>3</td>
            <td>21</td>
            <td>5</td>
        </tr>
        <tr>
            <td>Diego</td>
            <td>0</td>
            <td>5</td>
            <td>5</td>
        </tr>
        <tr>
            <td>Diferencial Imóveis</td>
            <td>0</td>
            <td>323</td>
            <td>0</td>
        </tr>
        <tr>
            <td>Diogo Dutra Claudiano</td>
            <td>3</td>
            <td>74</td>
            <td>4</td>
        </tr>
        <tr>
            <td>Emanuelle Vieira</td>
            <td>2</td>
            <td>21</td>
            <td>7</td>
        </tr>
        <tr>
            <td>Erick Willian Telles Justus</td>
            <td>3</td>
            <td>14</td>
            <td>6</td>
        </tr>
        <tr>
            <td>Fabiano Blan</td>
            <td>3</td>
            <td>36</td>
            <td>13</td>
        </tr>
        <tr>
            <td>Fabricio</td>
            <td>0</td>
            <td>62</td>
            <td>12</td>
        </tr>
        <tr>
            <td>Gabriel Polli Barbosa Neves</td>
            <td>5</td>
            <td>39</td>
            <td>14</td>
        </tr>
        <tr>
            <td>Guilherme Lemos Filho</td>
            <td>10</td>
            <td>0</td>
            <td>0</td>
        </tr>
        <tr>
            <td>Guilherme Matheus</td>
            <td>4</td>
            <td>13</td>
            <td>0</td>
        </tr>
        <tr>
            <td>Jeferson Marques</td>
            <td>1</td>
            <td>22</td>
            <td>3</td>
        </tr>
        <tr>
            <td>Jorge Matsumoto</td>
            <td>2</td>
            <td>69</td>
            <td>45</td>
        </tr>
        <tr>
            <td>Lais Moraes</td>
            <td>1</td>
            <td>73</td>
            <td>10</td>
        </tr>
        <tr>
            <td>Luciana Fraga</td>
            <td>0</td>
            <td>46</td>
            <td>25</td>
        </tr>
        <tr>
            <td>Marcelo</td>
            <td>1</td>
            <td>7</td>
            <td>3</td>
        </tr>
        <tr>
            <td>Mateus Godoi</td>
            <td>0</td>
            <td>39</td>
            <td>3</td>
        </tr>
        <tr>
            <td>Melissa Pizzano</td>
            <td>6</td>
            <td>49</td>
            <td>14</td>
        </tr>
        <tr>
            <td>Nathalia Nascimento</td>
            <td>1</td>
            <td>61</td>
            <td>6</td>
        </tr>
        <tr>
            <td>Nicolle Quevedo</td>
            <td>0</td>
            <td>47</td>
            <td>10</td>
        </tr>
        <tr>
            <td>Rafael Kubiski</td>
            <td>4</td>
            <td>20</td>
            <td>8</td>
        </tr>
        <tr>
            <td>Ricardo Luciano Gegenbauer Falkowski</td>
            <td>0</td>
            <td>39</td>
            <td>13</td>
        </tr>
        <tr>
            <td>Rodrigo Nicolas Falco</td>
            <td>0</td>
            <td>2</td>
            <td>0</td>
        </tr>
        <tr>
            <td>Waldir Alves</td>
            <td>0</td>
            <td>28</td>
            <td>7</td>
        </tr>
    </table>

    <h2>Insights e Análises</h2>
    <h3>Top Performers em Captações</h3>
    <p>Guilherme Lemos Filho é o corretor com o maior número de captações (10), seguido por Melissa Pizzano (6) e Gabriel Polli Barbosa Neves (5).</p>

    <h3>Top Performers em Atendimentos</h3>
    <p>Diferencial Imóveis lidera com 323 atendimentos, seguido por Diogo Dutra Claudiano (74) e Lais Moraes (73).</p>

    <h3>Top Performers em Visitas</h3>
    <p>Jorge Matsumoto realizou 45 visitas, seguido por Gabriel Polli Barbosa Neves e Melissa Pizzano, ambos com 14 visitas.</p>

    <h3>Correlacionando Captações e Visitas</h3>
    <p>Guilherme Lemos Filho fez 10 captações, mas não realizou atendimentos nem visitas, o que pode indicar um papel focado exclusivamente na captação.</p>
    <p>Jorge Matsumoto, com 69 atendimentos e 45 visitas, mostra um bom equilíbrio entre atender e converter clientes.</p>

    <h3>Eficiência dos Corretores</h3>
    <p>Analisando a relação entre atendimentos e visitas:</p>
    <ul>
        <li>Jorge Matsumoto realizou 69 atendimentos e 45 visitas, indicando uma alta taxa de conversão.</li>
        <li>Fabricio e Ricardo Luciano Gegenbauer Falkowski têm um número semelhante de visitas, mas Ricardo fez mais atendimentos.</li>
    </ul>

    <h2>Gráficos</h2>
    <div class="chart">
        <canvas id="chartCaptacoes"></canvas>
    </div>
    <div class="chart">
        <canvas id="chartAtendimentos"></canvas>
    </div>
    <div class="chart">
        <canvas id="chartVisitas"></canvas>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script>
        const ctxCaptacoes = document.getElementById('chartCaptacoes').getContext('2d');
        const chartCaptacoes = new Chart(ctxCaptacoes, {
            type: 'bar',
            data: {
                labels: ['Guilherme Lemos Filho', 'Melissa Pizzano', 'Gabriel Polli Barbosa Neves', 'Guilherme Matheus', 'Rafael Kubiski'],
                datasets: [{
                    label: 'Captações',
                    data: [10, 6, 5, 4, 4],
                    backgroundColor: 'rgba(54, 162, 235, 0.2)',
                    borderColor: 'rgba(54, 162, 235, 1)',
                    borderWidth: 1
                }]
            },
            options: {
                scales: {
                    y: {


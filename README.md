<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Entregadora Darton | Rapidez e Segurança</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        body { color: #333; background-color: #f9f9f9; }
        header { background: #1a252f; color: white; padding: 20px 50px; display: flex; justify-content: space-between; align-items: center; position: sticky; top: 0; z-index: 100; }
        header h1 { font-size: 24px; color: #f39c12; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: 500; }
        .btn-cta { background: #f39c12; color: white; padding: 10px 20px; border-radius: 5px; text-decoration: none; font-weight: bold; transition: 0.3s; }
        .btn-cta:hover { background: #e67e22; }
        
        .hero { background: linear-gradient(rgba(26, 37, 47, 0.8), rgba(26, 37, 47, 0.8)), url('https://images.unsplash.com/photo-1586528116311-ad8dd3c8310d?auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover; color: white; padding: 100px 50px; text-align: center; }
        .hero h2 { font-size: 42px; margin-bottom: 20px; }
        .hero p { font-size: 18px; margin-bottom: 30px; max-width: 600px; margin-left: auto; margin-right: auto; }
        
        .services { padding: 80px 50px; text-align: center; }
        .services h2 { font-size: 32px; margin-bottom: 40px; color: #1a252f; }
        .grid { display: flex; justify-content: center; gap: 30px; flex-wrap: wrap; }
        .card { background: white; padding: 30px; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); width: 300px; text-align: left; }
        .card h3 { color: #f39c12; margin-bottom: 15px; }
        
        footer { background: #1a252f; color: #bdc3c7; padding: 40px 50px; text-align: center; font-size: 14px; border-top: 4px solid #f39c12; }
        footer p { margin: 10px 0; }
        footer strong { color: white; }
    </style>
</head>
<body>

    <header>
        <h1>Entregadora Darton</h1>
        <nav>
            <a href="#inicio">Início</a>
            <a href="#servicos">Serviços</a>
            <a href="mailto:Dartonentregadora@gmail.com" class="btn-cta">Fale Conosco</a>
        </nav>
    </header>

    <section class="hero" id="inicio">
        <h2>Sua encomenda no destino certo, com a rapidez que você precisa.</h2>
        <p>A Entregadora Darton une pontualidade, segurança e eficiência para levar suas entregas sem complicações.</p>
        <a href="mailto:Dartonentregadora@gmail.com" class="btn-cta">Solicitar uma Entrega</a>
    </section>

    <section class="services" id="servicos">
        <h2>Nossos Serviços</h2>
        <div class="grid">
            <div class="card">
                <h3>Entregas Expressas</h3>
                <p>Perfeito para documentos e encomendas urgentes que precisam chegar no mesmo dia com total segurança.</p>
            </div>
            <div class="card">
                <h3>Logística para E-commerce</h3>
                <p>Parceria estratégica para lojas virtuais que desejam encantar clientes com entregas rápidas.</p>
            </div>
            <div class="card">
                <h3>Coletas Agendadas</h3>
                <p>Planeje suas demandas corporativas com rotas otimizadas e coletas programadas.</p>
            </div>
        </div>
    </section>

    <footer>
        <p><strong>Entregadora Darton</strong></p>
        <p>CNPJ: 58.903.352/0001-37 | E-mail: <a href="mailto:Dartonentregadora@gmail.com" style="color: #f39c12; text-decoration: none;">Dartonentregadora@gmail.com</a></p>
        <p>&copy; 2026 Entregadora Darton. Todos os direitos reservados.</p>
    </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EnglishAdventures | Ignite Your Fluency</title>
    <style>
        :root {
            --primary: #0984e3; 
            --accent: #e67e22;  
            --bg-color: #f0f3f7; 
            --text: #2d3436;
        }
        
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            background-color: var(--bg-color);
            background-image: radial-gradient(#d1d8e0 1px, transparent 1px);
            background-size: 30px 30px; 
            color: var(--text);
        }

        header {
            background: white;
            padding: 50px 20px;
            text-align: center;
            border-bottom: 6px solid var(--primary);
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }

        .hero-image {
            width: 100%;
            max-width: 800px;
            height: 300px;
            margin: 30px auto;
            background: url('https://images.unsplash.com/photo-1512820790803-83ca734da794?q=80&w=1000&auto=format&fit=crop') no-repeat center center;
            background-size: cover;
            border-radius: 20px;
            border: 4px solid white;
            box-shadow: 0 20px 40px rgba(0,0,0,0.15);
        }

        .container {
            max-width: 1000px;
            margin: 60px auto;
            padding: 50px;
            background: white;
            border-left: 15px solid var(--primary); 
            border-right: 2px solid #ddd;
            border-top: 2px solid #ddd;
            border-bottom: 2px solid #ddd;
            border-radius: 0 20px 20px 0;
            box-shadow: 25px 25px 0px rgba(9, 132, 227, 0.05);
        }

        .section {
            margin-bottom: 50px;
            padding-bottom: 30px;
            border-bottom: 1px solid #f1f1f1;
        }

        h1 { font-size: 3.5rem; margin: 0; color: var(--primary); }
        h2 { text-align: center; color: var(--primary); font-size: 2.2rem; }

        /* Testimonials Styling */
        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .testimonial-card {
            background: #f0f7ff;
            padding: 30px;
            border-radius: 15px;
            border-left: 5px solid var(--accent);
            font-style: italic;
            position: relative;
        }

        .testimonial-card::before {
            content: "“";
            font-size: 4rem;
            color: var(--accent);
            position: absolute;
            top: -10px;
            left: 10px;
            opacity: 0.3;
        }

        .student-name {
            display: block;
            margin-top: 15px;
            font-style: normal;
            font-weight: bold;
            color: var(--primary);
        }

        .pricing-grid {
            display: flex;
            gap: 30px;
            flex-wrap: wrap;
        }

        .pricing-card {
            flex: 1;
            min-width: 280px;
            padding: 40px 20px;
            background: #ffffff;
            border: 1px solid #dfe6e9;
            border-bottom: 8px solid #dfe6e9;
            border-radius: 15px;
            text-align: center;
        }

        .price { font-size: 3.5rem; font-weight: 900; color: var(--primary); }

        .contact-area {
            background: #f8f9fa;
            padding: 40px;
            border-radius: 15px;
            border: 1px solid #ddd;
            text-align: center;
        }

        .cta-button {
            display: inline-block;
            background: var(--accent);
            color: white;
            padding: 1.5rem 4rem;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.3rem;
            box-shadow: 0 10px 20px rgba(230, 126, 34, 0.3);
            transition: 0.3s;
            border: none;
        }

        .cta-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 25px rgba(230, 126, 34, 0.4);
        }

        footer {
            text-align: center;
            padding: 40px;
            color: #95a5a6;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

<header>
    <h1>EnglishAdventures</h1>
    <p style="font-size: 1.4rem;">Discover the World Through Language</p>
    <div class="hero-image"></div>
</header>

<div class="container">
    <section class="section">
        <div style="text-align: center;">
            <h2>Literary Free Talk</h2>
            <p style="font-size: 1.2rem; line-height: 1.8;">Transform your English from "basic" to "brilliant" through conversations inspired by world-class literature.</p>
        </div>
    </section>

    <section class="section">
        <h2>What Our Explorers Say</h2>
        <div class="testimonial-grid">
            <div class="testimonial-card">
                "I never thought I could discuss Shakespeare in English. This program gave me the confidence I needed to express complex ideas."
                <span class="student-name">— Elena, Club Member</span>
            </div>
            <div class="testimonial-card">
                "The private coaching sessions are intense but incredibly rewarding. My business English improved in just two months!"
                <span class="student-name">— Marco, Private Student</span>
            </div>
        </div>
    </section>

    <section class="section">
        <h2>Choose Your Journey</h2>
        <div class="pricing-grid">
            <div class="pricing-card">
                <h3>The Club</h3>
                <div class="price">$90</div>
                <p>Monthly Membership</p>
            </div>
            <div class="pricing-card" style="border-bottom-color: var(--primary);">
                <h3 style="color: var(--primary);">Private Coaching</h3>
                <div class="price">$150</div>
                <p>Monthly Membership</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact-area">
        <h2 style="margin-top: 0;">Ready to Begin?</h2>
        <p style="margin-bottom: 30px; color: #636e72;">Send me an email to schedule your first adventure.</p>
        
        <a href="mailto:yourname@email.com?subject=Inquiry about EnglishAdventures" class="cta-button">
            Email Me to Get Started
        </a>
    </section>
</div>

<footer>
    <p>&copy; 2026 EnglishAdventures. All rights reserved.</p>
</footer>

</body>
</html>

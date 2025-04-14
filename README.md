<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elevate Crowdfunding | Campaign Success Specialist</title>
    <style>
        :root {
            --primary: #6a5acd;
            --secondary: #ff7e5f;
            --dark: #2d2d44;
            --light: #f8f9fa;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            color: var(--dark);
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary), #8a7fff);
            color: white;
            padding: 2rem 0;
            text-align: center;
        }
        
        .container {
            width: 85%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }
        
        .logo {
            font-size: 1.8rem;
            font-weight: 700;
        }
        
        .nav-links a {
            color: white;
            text-decoration: none;
            margin-left: 2rem;
            font-weight: 500;
        }
        
        .hero {
            padding: 4rem 0;
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        
        .tagline {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 0 auto 2rem;
        }
        
        .cta-button {
            background-color: var(--secondary);
            color: white;
            padding: 0.8rem 2rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            display: inline-block;
            transition: transform 0.3s;
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
        }
        
        section {
            padding: 4rem 0;
        }
        
        h2 {
            text-align: center;
            font-size: 2.2rem;
            margin-bottom: 3rem;
            color: var(--primary);
        }
        
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .service-card {
            background: white;
            border-radius: 10px;
            padding: 2rem;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-10px);
        }
        
        .service-icon {
            font-size: 2.5rem;
            color: var(--primary);
            margin-bottom: 1rem;
        }
        
        .portfolio {
            background-color: var(--light);
        }
        
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .portfolio-item {
            position: relative;
            overflow: hidden;
            border-radius: 10px;
            height: 250px;
        }
        
        .portfolio-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s;
        }
        
        .portfolio-item:hover img {
            transform: scale(1.1);
        }
        
        .portfolio-overlay {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: rgba(106, 90, 205, 0.9);
            color: white;
            padding: 1rem;
            transform: translateY(100%);
            transition: transform 0.3s;
        }
        
        .portfolio-item:hover .portfolio-overlay {
            transform: translateY(0);
        }
        
        .testimonials .testimonial-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            margin: 1rem;
            position: relative;
        }
        
        .testimonial-card:before {
            content: '"';
            font-size: 5rem;
            color: var(--primary);
            opacity: 0.2;
            position: absolute;
            top: -1rem;
            left: 0.5rem;
        }
        
        .client-info {
            display: flex;
            align-items: center;
            margin-top: 1rem;
        }
        
        .client-info img {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            margin-right: 1rem;
            object-fit: cover;
        }
        
        footer {
            background-color: var(--dark);
            color: white;
            padding: 3rem 0;
            text-align: center;
        }
        
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 500;
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-family: inherit;
        }
        
        .form-group textarea {
            height: 150px;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.2rem;
            }
            
            .nav-links {
                display: none;
            }
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <div class="logo">Elevate Crowdfunding</div>
                <div class="nav-links">
                    <a href="#services">Services</a>
                    <a href="#portfolio">Portfolio</a>
                    <a href="#about">About</a>
                    <a href="#testimonials">Success Stories</a>
                    <a href="#contact">Contact</a>
                </div>
            </nav>
            
            <div class="hero">
                <h1>Turn Your Vision Into Funded Reality</h1>
                <p class="tagline">Specialized crowdfunding campaign management and promotion services to help innovative projects reach their funding goals and beyond.</p>
                <a href="#contact" class="cta-button">Get Your Free Consultation</a>
            </div>
        </div>
    </header>
    
    <section id="services">
        <div class="container">
            <h2>My Services</h2>
            <div class="services">
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-bullseye"></i>
                    </div>
                    <h3>Campaign Strategy</h3>
                    <p>Comprehensive planning including goal setting, reward structuring, timeline creation, and platform selection tailored to your project's unique needs.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-video"></i>
                    </div>
                    <h3>Video Production</h3>
                    <p>Professional crowdfunding video creation that tells your story compellingly and converts viewers into backers.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3>Marketing & Promotion</h3>
                    <p>Multi-channel promotion strategy including social media, PR outreach, email campaigns, and influencer partnerships to maximize visibility.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-users"></i>
                    </div>
                    <h3>Community Building</h3>
                    <p>Audience development and engagement strategies to build a loyal following before and during your campaign.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-comments-dollar"></i>
                    </div>
                    <h3>Backer Communication</h3>
                    <p>Professional updates and messaging to keep backers engaged and excited throughout the campaign and fulfillment process.</p>
                </div>
                
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-lightbulb"></i>
                    </div>
                    <h3>Post-Campaign Support</h3>
                    <p>Guidance on fulfillment, stretch goals, and maintaining momentum after your campaign ends.</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="portfolio" class="portfolio">
        <div class="container">
            <h2>Successful Campaigns</h2>
            <div class="portfolio-grid">
                <div class="portfolio-item">
                    <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Tech Gadget Campaign">
                    <div class="portfolio-overlay">
                        <h3>Nova Wireless Earbuds</h3>
                        <p>Raised $287,000 (287% of goal) on Kickstarter</p>
                    </div>
                </div>
                
                <div class="portfolio-item">
                    <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Cookbook Campaign">
                    <div class="portfolio-overlay">
                        <h3>Global Vegan Cookbook</h3>
                        <p>Raised $89,000 (445% of goal) on Indiegogo</p>
                    </div>
                </div>
                
                <div class="portfolio-item">
                    <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Board Game Campaign">
                    <div class="portfolio-overlay">
                        <h3>Eclipse Board Game</h3>
                        <p>Raised $153,000 (765% of goal) on Kickstarter</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <div style="max-width: 800px; margin: 0 auto; text-align: center;">
                <img src="https://images.unsplash.com/photo-1573497019940-1c28c88b4f3e?ixlib=rb-1.2.1&auto=format&fit=crop&w=300&q=80" alt="Profile Photo" style="width: 150px; height: 150px; border-radius: 50%; object-fit: cover; margin-bottom: 1.5rem;">
                <p>Hi, I'm Jordan Taylor, a crowdfunding specialist with over 7 years of experience helping creators launch successful campaigns. I've worked with over 50 projects across Kickstarter, Indiegogo, and other platforms, helping raise over $3.5 million collectively.</p>
                <p>My approach combines data-driven strategy with creative storytelling to create campaigns that resonate with backers. I understand what makes crowdfunding unique and how to leverage the psychology of backers to achieve exceptional results.</p>
                <p>When I'm not working on campaigns, you can find me speaking at crowdfunding workshops or writing about campaign strategies on my blog.</p>
            </div>
        </div>
    </section>
    
    <section id="testimonials" class="testimonials">
        <div class="container">
            <h2>What Clients Say</h2>
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem;">
                <div class="testimonial-card">
                    <p>"Jordan took our campaign from good to incredible. We exceeded our funding goal by 400% and gained thousands of new followers. Their marketing strategy was worth every penny."</p>
                    <div class="client-info">
                        <img src="https://randomuser.me/api/portraits/women/43.jpg" alt="Client">
                        <div>
                            <h4>Sarah Kim</h4>
                            <p>Founder, Nova Tech</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <p>"As first-time creators, we had no idea how to run a campaign. Jordan guided us through every step and helped us raise 5x our initial goal. The video they produced got us featured on Kickstarter's homepage!"</p>
                    <div class="client-info">
                        <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Client">
                        <div>
                            <h4>Michael Chen</h4>
                            <p>Creator, Eclipse Board Game</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <p>"After two failed attempts at crowdfunding, Jordan helped us completely rethink our approach. Our third campaign succeeded beyond our wildest expectations thanks to their expertise."</p>
                    <div class="client-info">
                        <img src="https://randomuser.me/api/portraits/women/65.jpg" alt="Client">
                        <div>
                            <h4>Lisa Rodriguez</h4>
                            <p>CEO, GreenLife Solutions</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <section id="contact">
        <div class="container">
            <h2>Ready to Launch?</h2>
            <p style="text-align: center; max-width: 600px; margin: 0 auto 2rem;">I offer free 30-minute consultations to discuss your project and how I can help make your campaign a success.</p>
            
            <div class="contact-form">
                <form>
                    <div class="form-group">
                        <label for="name">Your Name</label>
                        <input type="text" id="name" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="email">Email</label>
                        <input type="email" id="email" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="project">Project Type</label>
                        <input type="text" id="project" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="message">Tell me about your project</label>
                        <textarea id="message" required></textarea>
                    </div>
                    
                    <button type="submit" class="cta-button" style="border: none; cursor: pointer;">Send Message</button>
                </form>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <div class="logo" style="margin-bottom: 1.5rem;">Elevate Crowdfunding</div>
            <div style="display: flex; justify-content: center; gap: 2rem; margin-bottom: 2rem;">
                <a href="#" style="color: white;"><i class="fab fa-twitter fa-lg"></i></a>
                <a href="#" style="color: white;"><i class="fab fa-linkedin fa-lg"></i></a>
                <a href="#" style="color: white;"><i class="fab fa-instagram fa-lg"></i></a>
                <a href="#" style="color: white;"><i class="fab fa-kickstarter fa-lg"></i></a>
            </div>
            <p>&copy; 2023 Elevate Crowdfunding. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>

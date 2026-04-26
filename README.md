<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Automation Pro | PLC & HMI System Integrator</title>
    <link href="https://fonts.googleapis.com/css2?family=Chakra+Petch:wght@400;700&family=Sarabun:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-blue: #0a2e5c;
            --accent-orange: #ff7a00;
            --light-gray: #f8f9fa;
            --dark-text: #222;
        }

        body { font-family: 'Sarabun', sans-serif; margin: 0; color: var(--dark-text); scroll-behavior: smooth; }
        h1, h2, h3, .brand { font-family: 'Chakra Petch', sans-serif; }

        /* Header & Nav */
        header { 
            background: #fff; padding: 15px 8%; display: flex; justify-content: space-between; 
            align-items: center; position: sticky; top: 0; z-index: 1000; box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        .brand { font-size: 1.8rem; font-weight: 700; color: var(--primary-blue); }
        .brand span { color: var(--accent-orange); }
        nav a { margin-left: 20px; text-decoration: none; color: var(--dark-text); font-weight: bold; font-size: 0.9rem; }
        nav a:hover { color: var(--accent-orange); }

        /* Hero Section */
        .hero { 
            background: linear-gradient(135deg, rgba(10,46,92,0.9) 0%, rgba(10,46,92,0.7) 100%), 
                        url('https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&q=80&w=1920');
            background-size: cover; background-position: center;
            height: 70vh; display: flex; flex-direction: column; justify-content: center; align-items: center;
            color: white; text-align: center; padding: 0 20px;
        }
        .hero h1 { font-size: 3.5rem; margin: 0; letter-spacing: 2px; }
        .hero p { font-size: 1.3rem; max-width: 800px; margin: 20px 0; font-weight: 300; }

        /* Content Section */
        .section { padding: 80px 8%; }
        .title-box { text-align: center; margin-bottom: 50px; }
        .title-box h2 { font-size: 2.2rem; color: var(--primary-blue); position: relative; display: inline-block; }
        .title-box h2::after { content: ''; width: 60%; height: 4px; background: var(--accent-orange); position: absolute; bottom: -10px; left: 20%; }

        /* Tech Grid */
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; }
        .tech-card { 
            background: white; border-radius: 8px; padding: 35px; border-bottom: 5px solid var(--primary-blue);
            box-shadow: 0 5px 20px rgba(0,0,0,0.05); transition: 0.3s;
        }
        .tech-card:hover { transform: translateY(-10px); border-bottom-color: var(--accent-orange); }
        .tech-card h3 { color: var(--primary-blue); border-bottom: 1px solid #eee; padding-bottom: 15px; }
        .tech-card ul { list-style: none; padding: 0; }
        .tech-card ul li { padding: 8px 0; border-bottom: 1px inset #f9f9f9; font-weight: 500; }
        .tech-card ul li::before { content: '⚡'; margin-right: 10px; color: var(--accent-orange); }

        /* Call to Action */
        .cta { background: var(--primary-blue); color: white; padding: 60px 20px; text-align: center; }
        .btn { 
            background: var(--accent-orange); color: white; padding: 15px 40px; 
            text-decoration: none; font-weight: bold; border-radius: 5px; display: inline-block; margin-top: 20px;
        }

        footer { background: #111; color: #8892b0; padding: 40px 8%; text-align: center; }
    </style>
</head>
<body>

    <header>
        <div class="brand">AUTOMATION <span>PRO</span></div>
        <nav>
            <a href="#home">HOME</a>
            <a href="#plc">PLC SOLUTIONS</a>
            <a href="#hmi">HMI DESIGN</a>
            <a href="#contact">CONTACT</a>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>AUTOMATION <span>PRO</span></h1>
        <p>เชี่ยวชาญด้านระบบควบคุมอัตโนมัติ ออกแบบ ติดตั้ง และอัปเกรดระบบ PLC/HMI สำหรับโรงงานอุตสาหกรรมยุคใหม่</p>
        <a href="#contact" class="btn">ขอรับคำปรึกษาทางเทคนิค</a>
    </section>

    <section id="plc" class="section">
        <div class="title-box">
            <h2>PLC Programming Expertise</h2>
        </div>
        <div class="grid">
            <div class="tech-card">
                <h3>System Support</h3>
                <p>เรามีความเชี่ยวชาญในการเขียนโปรแกรม ปรับปรุง และแก้ไขระบบ PLC แบรนด์มาตรฐาน:</p>
                <ul>
                    <li>SIEMENS (TIA Portal / S7-Series)</li>
                    <li>MITSUBISHI (GX Works 2-3 / FX & Q Series)</li>
                    <li>KEYENCE (KV-8000 / KV-Series)</li>
                    <li>DELTA (DVP / AS / ISPSoft)</li>
                </ul>
            </div>
            <div class="tech-card">
                <h3>Our Services</h3>
                <ul>
                    <li>ออกแบบระบบควบคุมใหม่ (New Installation)</li>
                    <li>แก้ไข Logic และปรับปรุงประสิทธิภาพเครื่องจักร</li>
                    <li>ย้ายโปรแกรมจาก PLC รุ่นเก่า (Migration)</li>
                    <li>เชื่อมต่อระบบเครือข่ายอุตสาหกรรม (Modbus, CC-Link, Profinet)</li>
                </ul>
            </div>
        </div>
    </section>

    <section id="hmi" class="section" style="background: var(--light-gray);">
        <div class="title-box">
            <h2>HMI & Visualization</h2>
        </div>
        <div class="grid">
            <div class="tech-card" style="text-align: center;">
                <h4 style="color:var(--accent-orange)">MITSUBISHI HMI</h4>
                <p>ดีไซน์หน้าจอ GOT2000 Series ให้ดูง่าย ข้อมูลครบถ้วน</p>
            </div>
            <div class="tech-card" style="text-align: center;">
                <h4 style="color:var(--accent-orange)">DELTA HMI</h4>
                <p>โซลูชันหน้าจออัจฉริยะ ตอบโจทย์ทุกการเชื่อมต่อในราคามิตรภาพ</p>
            </div>
            <div class="tech-card" style="text-align: center;">
                <h4 style="color:var(--accent-orange)">SAMKOON HMI</h4>
                <p>ผู้เชี่ยวชาญการตั้งค่าหน้าจอ Samkoon คุ้มค่า ทนทาน ใช้งานได้จริง</p>
            </div>
        </div>
    </section>

    <div class="cta" id="contact">
        <h2>พร้อมยกระดับสายการผลิตของคุณหรือยัง?</h2>
        <p>Automation Pro พร้อมให้คำปรึกษาโดยทีมวิศวกรประสบการณ์ตรง</p>
        <p>📧 Email: contact@automation-pro.com | 📞 Tel:063-404-3661</p>
        <a href="mailto:contact@automation-pro.com" class="btn">ส่งข้อความหาเรา</a>
    </div>

    <footer>
        <p>&copy; 2026 Automation Pro Co., Ltd. | Expert in Industrial Control Systems.</p>
    </footer>

</body>
</html>

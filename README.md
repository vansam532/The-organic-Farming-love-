<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>जैविक खेती ऐप - डैशबोर्ड</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Devanagari:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header class="top-bar">
        <div class="app-name">जैविक खेती ऐप</div>
        <div class="header-icons">
            <select id="language-selector" class="language-selector">
                <option value="hi">हिंदी</option>
                <option value="en">English</option>
                <option value="es">Español</option>
            </select>
            <i class="fas fa-bell"></i>
            <i class="fas fa-user-circle"></i>
        </div>
    </header>

    <main class="dashboard-container">
        <div class="search-section">
            <div class="search-bar">
                <i class="fas fa-search"></i>
                <input type="text" placeholder="खोजें...">
            </div>
            <div class="location-date">
                <span id="current-location"><i class="fas fa-map-marker-alt"></i> नई दिल्ली, भारत</span>
                <span id="current-date"></span>
            </div>
        </div>

        <div class="hero-banner-container">
            <div class="hero-banner">
                <div class="banner-slide active" style="background-image: url('images/banner1.jpg');">
                    <div class="banner-content">
                        <h2>जैविक खेती का भविष्य</h2>
                        <p>प्राकृतिक तरीकों से बेहतर उपज पाएं</p>
                    </div>
                </div>
                <div class="banner-slide" style="background-image: url('images/banner2.jpg');">
                    <div class="banner-content">
                        <h2>स्वस्थ मिट्टी, स्वस्थ जीवन</h2>
                        <p>मिट्टी के स्वास्थ्य को समझें और सुधारें</p>
                    </div>
                </div>
            </div>
            <div class="banner-indicators">
                <span class="indicator active"></span>
                <span class="indicator"></span>
            </div>
        </div>

        <div class="dashboard-widget">
            <div class="metric-item">
                <i class="fas fa-thermometer-half icon-temp"></i>
                <span class="metric-value">28°C</span>
                <span class="metric-label">तापमान</span>
            </div>
            <div class="metric-item">
                <i class="fas fa-water icon-humidity"></i>
                <span class="metric-value">75%</span>
                <span class="metric-label">आर्द्रता</span>
            </div>
            <div class="metric-item">
                <i class="fas fa-flask icon-ph"></i>
                <span class="metric-value">6.8</span>
                <span class="metric-label">मिट्टी pH</span>
            </div>
        </div>

        <h3 class="section-title">मुख्य सुविधाएँ</h3>
        <div class="main-features-grid">
            <div class="feature-tile" onclick="alert('ज्ञानकोश पर जाएँ');">
                <i class="fas fa-book icon-feature"></i>
                <span>ज्ञानकोश</span>
            </div>
            <div class="feature-tile" onclick="alert('मिट्टी विश्लेषक पर जाएँ');">
                <i class="fas fa-flask icon-feature"></i>
                <span>मिट्टी विश्लेषक</span>
            </div>
            <div class="feature-tile" onclick="alert('मार्केटप्लेस पर जाएँ');">
                <i class="fas fa-store icon-feature"></i>
                <span>मार्केटप्लेस</span>
            </div>
            <div class="feature-tile" onclick="alert('समुदाय पर जाएँ');">
                <i class="fas fa-users icon-feature"></i>
                <span>समुदाय</span>
            </div>
            <div class="feature-tile" onclick="alert('सरकारी योजनाओं पर जाएँ');">
                <i class="fas fa-handshake icon-feature"></i>
                <span>सरकारी योजनाएँ</span>
            </div>
            <div class="feature-tile" onclick="alert('मौसम सलाह पर जाएँ');">
                <i class="fas fa-cloud-sun icon-feature"></i>
                <span>मौसम सलाह</span>
            </div>
        </div>

        <h3 class="section-title">जैविक खेती ज्ञानकोश</h3>
        <div class="knowledge-base-section">
            <div class="knowledge-item" onclick="alert('जैविक खाद बनाने के तरीके के बारे में जानें');">
                <div class="item-icon"><i class="fas fa-leaf"></i></div>
                <div class="item-content">
                    <h4>जैविक खाद बनाने के तरीके</h4>
                    <p>कम्पोस्ट, वर्मीकम्पोस्ट और अन्य जैविक खाद बनाने की विधि सीखें।</p>
                </div>
                <div class="item-arrow"><i class="fas fa-chevron-right"></i></div>
            </div>
            <div class="knowledge-item" onclick="alert('जैविक कीट नियंत्रण के बारे में जानें');">
                <div class="item-icon"><i class="fas fa-bug"></i></div>
                <div class="item-content">
                    <h4>जैविक कीट नियंत्रण</h4>
                    <p>फसलों को कीटों से बचाने के प्राकृतिक और सुरक्षित उपाय।</p>
                </div>
                <div class="item-arrow"><i class="fas fa-chevron-right"></i></div>
            </div>
            <div class="knowledge-item" onclick="alert('जैविक प्रमाणीकरण प्रक्रिया के बारे में जानें');">
                <div class="item-icon"><i class="fas fa-award"></i></div>
                <div class="item-content">
                    <h4>जैविक प्रमाणीकरण प्रक्रिया</h4>
                    <p>जैविक उत्पादों के लिए अंतर्राष्ट्रीय और राष्ट्रीय प्रमाणीकरण कैसे प्राप्त करें।</p>
                </div>
                <div class="item-arrow"><i class="fas fa-chevron-right"></i></div>
            </div>
        </div>
    </main>

    <footer class="bottom-nav">
        <div class="nav-item active">
            <i class="fas fa-home"></i>
            <span>होम</span>
        </div>
        <div class="nav-item">
            <i class="fas fa-book"></i>
            <span>ज्ञानकोश</span>
        </div>
        <div class="nav-item">
            <i class="fas fa-store"></i>
            <span>बाज़ार</span>
        </div>
        <div class="nav-item">
            <i class="fas fa-users"></i>
            <span>समुदाय</span>
        </div>
        <div class="nav-item">
            <i class="fas fa-user-circle"></i>
            <span>प्रोफाइल</span>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>


<!DOCTYPE html>
<html lang="he">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LifePilot - האפליקציה שמארגנת את החיים שלך</title>
  <link href="https://fonts.googleapis.com/css2?family=Alef&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Alef', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f6f8fb;
      color: #222;
      direction: rtl;
    }
    header {
      background-color: #1a73e8;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background-color: #e3edf7;
      padding: 1rem;
    }
    nav a {
      text-decoration: none;
      color: #1a73e8;
      font-weight: bold;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    .features {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
    }
    .feature {
      flex: 1 1 250px;
      background: white;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .download-buttons a {
      display: inline-block;
      margin: 1rem 1rem 0 0;
      padding: 1rem 1.5rem;
      background: #1a73e8;
      color: white;
      border-radius: 8px;
      text-decoration: none;
    }
    footer {
      background: #1a73e8;
      color: white;
      text-align: center;
      padding: 2rem;
      margin-top: 2rem;
    }
    .language-switcher {
      text-align: center;
      margin: 1rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>LifePilot</h1>
    <p>האפליקציה שתעזור לך לנהל את החיים שלך בצורה חכמה, רגועה ויעילה</p>
    <div class="download-buttons">
      <a href="#">הורד לאייפון</a>
      <a href="#">הורד לאנדרואיד</a>
    </div>
  </header>

  <nav>
    <a href="#about">מה זה LifePilot?</a>
    <a href="#features">יתרונות</a>
    <a href="#team">עלינו</a>
    <a href="#blog">בלוג</a>
    <a href="#contact">צור קשר</a>
  </nav>

  <div class="language-switcher">
    <p>בחר שפה: <a href="#">עברית</a> | <a href="#">English</a> | <a href="#">العربية</a> | <a href="#">Русский</a></p>
  </div>

  <section id="about">
    <h2>מה זה LifePilot?</h2>
    <p>
      LifePilot היא אפליקציה חדשנית שתוכננה במיוחד כדי לעזור לך לעשות סדר בחיים – עם לוחות זמנים חכמים, תזכורות חכמות, סנכרון עם משפחה, משימות יומיות, ושילוב עם אפליקציות כמו WhatsApp ו־Google Calendar. היא מתאימה במיוחד להורים עסוקים, חיילים, יזמים וסטודנטים שרוצים להרגיש בשליטה.
    </p>
  </section>

  <section id="features">
    <h2>יתרונות מרכזיים</h2>
    <div class="features">
      <div class="feature">
        <h3>⏱️ חוסך זמן</h3>
        <p>ניהול משימות חכם, תזכורות אוטומטיות ותכנון יומי שמשאיר אותך ממוקד.</p>
      </div>
      <div class="feature">
        <h3>🧘 סדר אישי רגוע</h3>
        <p>אפליקציה שלא מציפה אותך – אלא מארגנת אותך. עם ממשק נעים ופשוט.</p>
      </div>
      <div class="feature">
        <h3>👨‍👩‍👧‍👦 מסנכרן את כל המשפחה</h3>
        <p>שתף אירועים, רשימות ומשימות בין בני המשפחה. סוף לבלאגן.</p>
      </div>
      <div class="feature">
        <h3>🔗 חיבור לאפליקציות אחרות</h3>
        <p>מתממשק עם גוגל, וואטסאפ, לוחות שנה ועוד.</p>
      </div>
    </div>
  </section>

  <section id="team">
    <h2>עלינו</h2>
    <p>
      LifePilot נוסדה על ידי צוות של יזמים, אנשי הייטק, קצינים לשעבר בצה"ל והורים לחיי משפחה עמוסים. כולנו הבנו שהחיים נהיים מורכבים – ושהפתרונות צריכים להיות פשוטים. לכן בנינו את LifePilot. אפליקציה שבאמת עוזרת.
    </p>
  </section>

  <section id="blog">
    <h2>מה חדש בבלוג?</h2>
    <p>בקרוב יתפרסמו כאן מאמרים על ניהול זמן, איזון בית-עבודה, טכנולוגיה בשירות המשפחה, טיפים אפקטיביים ועוד.</p>
  </section>

  <section id="contact">
    <h2>צור קשר</h2>
    <p>יש לכם שאלה? בקשה? שיתוף פעולה? כתבו לנו:</p>
    <form>
      <input type="text" placeholder="שם מלא" required><br><br>
      <input type="email" placeholder="דוא"ל" required><br><br>
      <textarea placeholder="הודעה" rows="5" required></textarea><br><br>
      <button type="submit">שלח</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 LifePilot. כל הזכויות שמורות.</p>
  </footer>

</body>
</html>

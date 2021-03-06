
# FinalProject-OceanBalance    
### A game that tests your balance ability.
     
### :video_game: [PLAY ON ITCH.IO](https://game-dev-project-d-a-y.itch.io/ocean-balance) :video_game:
    
    
## About the Devlopment of our Game:     

### Main Elements of the game  
<img src= https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/base.jpg width="400" height="200"/>
   
**Ball** - Has a RigidBody component which allows it to roll around the surface and a [BallScript script](https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Assets/Scripts/BallScript.cs) which sends to the GameManager commands as soon as it colides with a bottle/whole/border.   
 
**Base** - The surface of the game which is controled by the [Mover Script](https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Assets/Scripts/Mover.cs)
    
**Bottle** - Every N seconds it appears on the surface and disappears when the ball coliides with it or when it times out (every bottle has a few seconds to be touched and when a player does not make it, a **black hole** appears instead of the bottle and the player should **Not** touch the hole with the ball.   

### GameManager
In our project we created a [GameManager script](https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Assets/GameManager.cs) which through it we control the game.
The pointes, timer and amount of bottles collected are also controlled in this script and all of three have the Text Mesh Pro component.

### Design    
To deisgn the sea under the base, we used a Shader. If you are no fammiliar with the unity Shader you may watch this video on [YouTube: Water Shader](https://www.youtube.com/watch?v=Vg0L9aCRWPE&t=302s).   

<img src= https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Images/sea.jpg width="300" height="150"/>
    
    
## So What are you waiting for? Go Save our Sea Friends    
<img src= https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Images/save%20the%20sea.jpg width="520" />

 
<div dir="rtl">    

### נאום מעלית

העולם שלנו מתחיל להיהרס !
דרושה פעולה מיידית של כל אחד מאיתנו !
המשחק הזה מהנה בטירוף, תחרותי, כיפי ומשפר ביצועים מוטוריים עדינים אך עם זאת, מחביא בתוכנו מטרה עילאית והיא הטמעת עניין שמירת העולם וקיימות, בדרך צעירה כיפית ומשחקית.
אתה גם משחק גם שובר שיאים וגם מרגיש שאתה מציל את העולם 
אז  
let's Balance the Ocean


### סוג המשחק ולמי מתאים

המשחק הוא תחרותי ו"קוויקי" ולכן קהל היעד של המשחק הוא כל אדם שאוהב משחקים מהירים ממכרים כאשר הרמה עולה מרגע לרגע בנוסף המשחק הוא תחרותי-אישי ומי שאוהב לשבור שיאים של עצמו לבחון את יכולותיו יהנה מאוד מהמשחק הזה.
המשחק גם מדבר אל חובבי הטבע שרוצים לשמור על החיות ולהפיץ מודעות חיובית בנושא

### פלטפורמת עבודה

המשחק מתאים גם למחשב וגם לטלפון נייד.
בטלפון נייד היתרון הוא שימוש באיזון הבנוי הקיים במכשיר הטלפוני, עוד במחשב התזוזה תהיה ע"י החיצים.


### לאילו גילאים

.המשחק דורש מוטרוקיה עדינה וכל אדם בעל יכולות פיזיות תקינות יכול לשחק במשחק זה. 
 המשחק מיועד לגילאי 7+ בגיל זה היכולות המוטוריות יחסית טובות ויכולות להתפתח תוך כדי המשחק עצמו.
בנוסף בעלי חיבה לחיות ואיכות הסביבה ימצאו הנאה רבה במטרה המשנית של המשחק שהיא העלאת המודעות לאיכות הסביבה ושמירה על העולם.


## כמה שחקנים:

המשחק מיועד לשחקן יחיד



# מטרת המשחק

מטרת השחקן היא להשאיר כמה שיותר זמן את הכדור על המשטח
כדי לעשות זאת ישתמש בתבונה וברגישות בחיצים אך עם זאת ינסה לאסוף את עצמי הפלסטיק על מנת שלא יפערו במקומם "חורים שחורים" שיקשו על השחקן את המשחק.

### מסך הפתיחה

#### כפי שניתן לראות במסך זה מוצג שם המשחק וכפתור "התחלה" שבלחיצה עליו נעבור למסך הבא
<img src= https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Images/openScreen.png width="600" height="400"/>

<img src= https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Images/openScreenafterstart.png width="600" height="400"/>

לאחר לחיצה על כפתור "התחלה" יפתח מסך נוסף עם 3 כפתורים 
* טעינת המשחק
* הסבר 
* save the  Sea


### המשחק עצמו
<img src= https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Images/thegame.png width="600" height="400"/>


### מה לעשות כדי לשחק ?
כפי שניתן לראות בתמונת המשחק הראשונה התזוזה היא ע"י "החיצים" במקלדת . ע"י הזזת החיצים המשטח יוטה לכיוון שהשחקן בחר והכדור "יפול" וימשיך בכיוון זה.
בתחילת המשחק יופיעו החיצים שיזכירו לשחקן איך לשחק 
לאחר התחלת המשחק יעלמו החיצים ותיחילו להופיע "עצמי הפלסטיק" שאותם השחקן ינסה לאסוף .
בנוסף מימד הזמן יתחיל ברגע שילחץ על אחד החיצים.

<img src= https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Images/thegame2.png width="600" height="400"/>

כפי שניתן לראות המשטח בהטייה כלומר השחקן התחיל במשחק ומנסה לשמור את הכדור על המשטח. כמו כן ניתן לראות את בקבוק הפלסטיק 
ושהשחקן מנסה להגיע אליו ולאסוף אותו.
  
### לאחר אי אסיפת פריט פלסטיק  
<img src= https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Images/gamebalckhole.png width="600" height="400"/>


השחקן לא מצליח לקחת את הבקבוק ובמקומו מופיע "חור שחור" שבמקרה והכדור יפול אליו השחקן ייפסל. 

### סיום המשחק

המשחק נגמר כאשר  הכדור יוצא מגבולות המשטח או כאשר הכדור נופל לאחד החורים שמצויים על המשטח.
הזמן שהשחקן שרד זה התוצאה הסופית שלו והיא נשמרת בטבלת השיאים אם תוצאתו תהיה גבוהה מספיק.
בהתאם למספר הבקבוקים שהשחקן אסף יופיע טקטס שיגיד לשחקן כמה צבי ים הוא הציל בעזרת הבקבוקים שאסף.

השחקן לא הצליח לשמור את הכדור על המשטח כי קרו אחת מ-2 הסיבות הבאות:
* הכדור נפל ויצא מגבולות המשטח
* הכדור נכנס לאחד "מהחורים השחורים" ודרכם הכדור "נפל" מהמשטח

לכן השחקן הפסיד ויופיעו המסכים הבאים:

<img src= https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Images/theEnd2.png width="600" height="400"/>
<img src= https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Images/theEnd.png width="600" height="400"/>


### העצמים במשחק
למשחק זה יש מספר עצמים 
* הכדור-העצם המרכזי שדרכו ניתן לאסוף "עצמי פלסטיק" וכל זמן הישארותו במשחק הזמן ממשיך לרוץ
* המשטח- החלק המרכזי שאחראי על תזוזת הכדור 
* בקבוקי הפלסטיק-עוזרים לנו לשמור על תוצאה גדולה יותר כמו כן איסוף של בקבוקי פלסטיק יעניקו לך "צב" שהצלת 
* חורים שחורים- מופיעים כאשר לא הצלחת לאסוף פריט פלסטיק, חורים אלו יקשו על המשחק שכן אסור לכדור להכינס אליהם



### צורת משחק
 שחקן יכול לבחור איך לשחק :
* האם ינסה לאסוף בקבוקי פלסטיק ולצבע לפעמים תמרונים חדים כדי לשמור על העולם ושלא יפערו חורים במקומו
* לא ללנסות להילחם על כל בקבוק ואז התמורנים יותר עדינים אבל יש יותר חורים במשחק


### קושי המשחק
ככל שהזמן במשחק גדל רמת הקושי עולה בהתאם 
אם ע"י הופעת יותר חורים שחורים ואם ע"י קיצור זמן הופעת עצמי הפלסטיק


###  חוקים ועולם המשחק

חוקי תזוזה – המקשים היחידים שבשימוש הם מקשי החצים. כל חץ יזיז את המשטח לכיוונו של החץ.

שני חוקי פסילה עיקריים
*	אם הכדור נופל מהמשטח אז המשחק מסתיים.
*	אם הכדור נופל לחור שחור המשחק נעצר.
על כל בקבוק שנאסף במהלך המשחק יופיע עוד כדור. אם השחקן מפספס את הבקבוק אז יופיע בנוסף לבקבוק חדש גם חור שחור במיקום חדש.

למידת החוקים
למידת החוקים יהיו בתחילת המשחק בדף ההוראות למרות שהמשחק הזה חוקיו פשוטים ואחרי משחק אחד או שניים יהיה ניתן להבין את המשחק.

העולם הינו סגור, כל המשחק מתרכז בנקודה אחת.
יש את גבולות המשטח שהם המשטח עצמו.
בנוסף לגבולות המשטח יש את גבולות החורים השחורים שלכל אחד יש גבול שלו ועל השחקן להימנע מהם גם כן.
כדי שהשחקן יוכל לראות את הטיית המשטח בשלמותו.
העולם של המשחק יהיה בתלת מימד


### הסיפור מאחרי המשחק
 בכל שנה מעל מיליון חיות ים נפגעות מפסולת ימית ונזרקים מעל מאה טונות של פלסטיק אל תוך הים. אנו רוצים להציל את הצבי ים הנפגעים כל שנה מפסולת ימית. בכדי שנציל אותם אנחנו צריכים לאסוף כמה שיותר פלסטיק לפני שיפול לים.
כל עיצוב המשחק בנוי סביב אנקדוטה זו.


### שלבי המשחק
המשחק הוא שלב אחד שרמת הקושי בו עולה בהדרגתיות תוך כדי.
ישנם בקבוקים עם זמן שצריך לאסוף וזמן זה מתקצר עם התקדמות המשחק
ישנם חורים שחורים שמופיעים במקום בקבוקי הםלסטיק במקרה ולא נאספו
יש את מדד הזמן שמפעיל חץ על השחקן כאשר מתקרב לשבירת השיא- לחץ מוביל בדרך כלל גם לטעויות אז השחקן מתעמת עם עצמו


### סקר שוק

חיפשנו במשך הרבה זמן משחק כמו שלנו, מצאנו משחקים עם בסיס דומה שהוא הזזה של כדור באמצעות תזוזה של משטח מסויים
אבל אף לא אחד מהם דומה לשלנו הן מבחינת המשחק עצמו והן מבחינת הסיפור וצורת המשחק.
המשחקים שמצאנו מזיזים כדור על גבי מסלול ולא משטח.

ייחודיות המשחק שלנו מתבטאת גם בשיטת המשחק שהיא צורת מצחק מהירה וללא שלבים
משחק שכיף לשחק ולשבור שיאים ולא משחק "כבד" שאתה צריך לעבור בו שלבים, לשמור מצב ולהמשיך ממנו.
בנוסף עניין אסיפת המוצרים והמכשולים מאוד ייחודיים וטומני מאחריהם עלילה חשובה שמטרתה
לחזק אצל השחקנים המשחקים את עניין איכות הסביבה ושמירה על האוקיינוס.

### King Of Opera
<img src= https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Images/kingofopera.png width="400" height="200"/>

זהו משחק של 4 שחקנים שמטרתם להפיל את היריבים אל מחוץ לגבולות המשטח , דומה לשלנו מסחינת המשטח והחוקים האסורים שהם אסור ליפול מהשטח ושונה בכל השאר

### BallBallance3D
<img src= https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Images/ballballance3d.png width="300" height="150"/>

זהו משחק של שחקן יחיד שבו הוא מוביל כדור לאורך מסלולים שונים ומטרתו לא להפיל את הכדור
דומה לשלנו מבחינת מטרת המשחק לא להפיל את הכדור ושונה בכל השאר מבחינת הצורה של המשחק הדרך לשחק ושיטת הניקוד

### other games like Ball Ballance
<img src= https://github.com/Game-Dev-Project-D-A-Y/OceanBalance/blob/main/Images/listlikeourgame.png width="130" height="300"/>




</div>


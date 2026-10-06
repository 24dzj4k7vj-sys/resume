# resume<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Әділер Ақбергенов | Chemical Engineer</title>

    <meta name="description"
          content="Әділер Ақбергенов — Chemical Engineer / Laboratory Specialist. Chemical and instrumental analysis, AAS, ICP-OES, XRF.">

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        :root {
            --bg: #f4f6f8;
            --card: #ffffff;
            --dark: #101827;
            --text: #1f2937;
            --muted: #6b7280;
            --blue: #2563eb;
            --blue-light: #eff6ff;
            --border: #e5e7eb;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI",
                         Roboto, Arial, sans-serif;
            background: var(--bg);
            color: var(--text);
            line-height: 1.65;
        }

        a {
            color: inherit;
            text-decoration: none;
        }

        .container {
            max-width: 1100px;
            margin: auto;
            padding: 25px;
        }

        /* LANGUAGE */

        .language-switcher {
            display: flex;
            justify-content: flex-end;
            gap: 8px;
            margin-bottom: 15px;
        }

        .language-switcher button {
            border: 1px solid var(--border);
            background: white;
            padding: 8px 15px;
            border-radius: 9px;
            cursor: pointer;
            font-weight: 600;
        }

        .language-switcher button:hover {
            background: var(--blue-light);
            color: var(--blue);
        }

        /* HEADER */

        .hero {
            background: var(--dark);
            color: white;
            border-radius: 24px;
            padding: 50px;
            margin-bottom: 22px;
        }

        .hero h1 {
            font-size: 44px;
            margin-bottom: 8px;
            letter-spacing: -1px;
        }

        .hero .position {
            font-size: 21px;
            color: #cbd5e1;
            margin-bottom: 25px;
        }

        .contacts {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .contact {
            background: rgba(255,255,255,0.08);
            border: 1px solid rgba(255,255,255,0.08);
            padding: 8px 13px;
            border-radius: 10px;
            color: #e5e7eb;
            font-size: 14px;
        }

        /* LAYOUT */

        .layout {
            display: grid;
            grid-template-columns: 1.55fr 0.85fr;
            gap: 22px;
        }

        .card {
            background: var(--card);
            border: 1px solid var(--border);
            border-radius: 18px;
            padding: 28px;
            margin-bottom: 22px;
        }

        .card h2 {
            font-size: 22px;
            margin-bottom: 17px;
            color: var(--dark);
        }

        .card h3 {
            font-size: 18px;
            margin-bottom: 4px;
            color: var(--dark);
        }

        .subtitle {
            color: var(--muted);
            margin-bottom: 12px;
            font-size: 14px;
        }

        .card p {
            color: #4b5563;
        }

        ul {
            padding-left: 21px;
        }

        li {
            margin-bottom: 8px;
        }

        .divider {
            border: none;
            border-top: 1px solid var(--border);
            margin: 25px 0;
        }

        /* TAGS */

        .tags {
            display: flex;
            flex-wrap: wrap;
            gap: 9px;
        }

        .tag {
            background: var(--blue-light);
            color: #174ea6;
            border-radius: 30px;
            padding: 7px 12px;
            font-size: 13px;
            font-weight: 600;
        }

        /* LANGUAGE CONTENT */

        .language-content {
            display: none;
        }

        .language-content.active {
            display: block;
        }

        /* FOOTER */

        footer {
            text-align: center;
            color: var(--muted);
            padding: 5px 0 30px;
            font-size: 13px;
        }

        /* MOBILE */

        @media (max-width: 800px) {

            .container {
                padding: 15px;
            }

            .hero {
                padding: 32px 24px;
                border-radius: 20px;
            }

            .hero h1 {
                font-size: 32px;
            }

            .hero .position {
                font-size: 18px;
            }

            .layout {
                grid-template-columns: 1fr;
            }

            .card {
                padding: 22px;
            }
        }
    </style>
</head>


<body>

<div class="container">

    <!-- LANGUAGE SWITCHER -->

    <div class="language-switcher">
        <button onclick="changeLanguage('ru')">RU</button>
        <button onclick="changeLanguage('en')">EN</button>
    </div>


    <!-- ===================== RUSSIAN ===================== -->

    <div id="ru" class="language-content active">

        <header class="hero">

            <h1>Әділер Ақбергенов</h1>

            <div class="position">
                Инженер-химик / Специалист лаборатории
            </div>

            <div class="contacts">

                <div class="contact">
                    🇰🇿 Казахстан
                </div>

                <div class="contact">
                    🧪 Химический и инструментальный анализ
                </div>

                <div class="contact">
                    ⚙️ AAS · ICP-OES · XRF
                </div>

            </div>

        </header>


        <div class="layout">

            <main>

                <!-- PROFILE -->

                <section class="card">

                    <h2>Профессиональный профиль</h2>

                    <p>
                        Инженер-химик / специалист лаборатории с опытом работы
                        в химическом и инструментальном анализе руд, фосфоритов,
                        золота, меди, молибдена, серебра и других материалов.
                    </p>

                    <br>

                    <p>
                        Владею методами ААС, ICP-OES, РФА, гравиметрического,
                        титриметрического и пробирного анализа. Имею опыт
                        подготовки проб, приготовления реактивов и растворов,
                        калибровки оборудования, контроля качества и ведения
                        лабораторной документации.
                    </p>

                </section>


                <!-- EXPERIENCE -->

                <section class="card">

                    <h2>Опыт работы</h2>


                    <h3>
                        Инженер / производственно-техническое направление
                    </h3>

                    <div class="subtitle">
                        Производственно-техническая деятельность
                    </div>

                    <ul>

                        <li>
                            Участие в разработке и оптимизации технологических
                            процессов.
                        </li>

                        <li>
                            Анализ производственных показателей и результатов
                            лабораторных исследований.
                        </li>

                        <li>
                            Контроль качества технологических процессов.
                        </li>

                        <li>
                            Подготовка производственно-технической документации
                            и отчётности.
                        </li>

                        <li>
                            Взаимодействие с лабораторными и производственными
                            подразделениями.
                        </li>

                    </ul>


                    <hr class="divider">


                    <h3>
                        Лабораторный специалист — химический анализ
                    </h3>

                    <div class="subtitle">
                        Химический и инструментальный анализ
                    </div>

                    <ul>

                        <li>
                            Проведение химического анализа проб золота,
                            меди, молибдена, серебра, фосфоритов и других
                            материалов.
                        </li>

                        <li>
                            Гравиметрический, титриметрический и пробирный
                            анализ.
                        </li>

                        <li>
                            Подготовка проб: дробление, измельчение,
                            минерализация и химическое разложение.
                        </li>

                        <li>
                            Приготовление химических реактивов, рабочих,
                            стандартных и калибровочных растворов.
                        </li>

                        <li>
                            Калибровка лабораторного оборудования.
                        </li>

                        <li>
                            Проведение внутреннего контроля качества
                            аналитических результатов.
                        </li>

                        <li>
                            Ведение лабораторной документации и оформление
                            результатов анализов.
                        </li>

                    </ul>

                </section>


                <!-- EQUIPMENT -->

                <section class="card">

                    <h2>Оборудование и методы</h2>

                    <div class="tags">

                        <span class="tag">AAS</span>

                        <span class="tag">ICP-OES</span>

                        <span class="tag">XRF / РФА</span>

                        <span class="tag">Agilent 5100</span>

                        <span class="tag">
                            Thermo Scientific iCAP PRO
                        </span>

                        <span class="tag">
                            Epsilon 3XL
                        </span>

                        <span class="tag">
                            РЛП-21
                        </span>

                        <span class="tag">
                            LECO
                        </span>

                        <span class="tag">
                            Spectroscan
                        </span>

                    </div>

                </section>

            </main>


            <aside>

                <!-- SKILLS -->

                <section class="card">

                    <h2>Ключевые навыки</h2>

                    <ul>

                        <li>Химический анализ</li>

                        <li>Инструментальный анализ</li>

                        <li>Подготовка проб</li>

                        <li>Приготовление растворов</li>

                        <li>Гравиметрический анализ</li>

                        <li>Титриметрический анализ</li>

                        <li>Пробирный анализ</li>

                        <li>Калибровка оборудования</li>

                        <li>Контроль качества</li>

                        <li>Лабораторная документация</li>

                        <li>
                            ГОСТ, ISO, ТУ и внутренние методики
                        </li>

                        <li>
                            Промышленная безопасность и охрана труда
                        </li>

                    </ul>

                </section>


                <!-- EDUCATION -->

                <section class="card">

                    <h2>Образование</h2>

                    <h3>
                        М.Х. Дулати атындағы
                        Тараз өңірлік университеті
                    </h3>

                    <p>
                        Бакалавр
                    </p>

                    <p>
                        Химическая инженерия и процессы
                    </p>

                </section>


                <!-- ADDITIONAL -->

                <section class="card">

                    <h2>Дополнительно</h2>

                    <ul>

                        <li>
                            Работа с лабораторными и производственными
                            подразделениями.
                        </li>

                        <li>
                            Обучение и адаптация новых сотрудников.
                        </li>

                        <li>
                            Передача практического опыта новым работникам.
                        </li>

                    </ul>

                </section>

            </aside>

        </div>

    </div>


    <!-- ===================== ENGLISH ===================== -->

    <div id="en" class="language-content">

        <header class="hero">

            <h1>Әділер Ақбергенов</h1>

            <div class="position">
                Chemical Engineer / Laboratory Specialist
            </div>

            <div class="contacts">

                <div class="contact">
                    🇰🇿 Kazakhstan
                </div>

                <div class="contact">
                    🧪 Chemical & Instrumental Analysis
                </div>

                <div class="contact">
                    ⚙️ AAS · ICP-OES · XRF
                </div>

            </div>

        </header>


        <div class="layout">

            <main>

                <!-- PROFILE -->

                <section class="card">

                    <h2>Professional Summary</h2>

                    <p>
                        Chemical Engineer / Laboratory Specialist with
                        experience in chemical and instrumental analysis
                        of ores, phosphorites, gold, copper, molybdenum,
                        silver, and other materials.
                    </p>

                    <br>

                    <p>
                        Skilled in AAS, ICP-OES, XRF, gravimetric,
                        titrimetric, and fire assay methods. Experienced
                        in sample preparation, reagent and solution
                        preparation, equipment calibration, quality control,
                        and laboratory documentation.
                    </p>

                </section>


                <!-- EXPERIENCE -->

                <section class="card">

                    <h2>Work Experience</h2>


                    <h3>
                        Engineer / Production & Technical Operations
                    </h3>

                    <div class="subtitle">
                        Production and technical activities
                    </div>

                    <ul>

                        <li>
                            Participated in process development and
                            optimization.
                        </li>

                        <li>
                            Analyzed production data and laboratory results.
                        </li>

                        <li>
                            Monitored process quality and performance.
                        </li>

                        <li>
                            Prepared technical documentation and reports.
                        </li>

                        <li>
                            Coordinated with laboratory and production
                            departments.
                        </li>

                    </ul>


                    <hr class="divider">


                    <h3>
                        Laboratory Specialist — Chemical Analysis
                    </h3>

                    <div class="subtitle">
                        Chemical and instrumental analysis
                    </div>

                    <ul>

                        <li>
                            Conducted chemical analysis of gold, copper,
                            molybdenum, silver, phosphorite, and other
                            samples.
                        </li>

                        <li>
                            Performed gravimetric, titrimetric, and fire
                            assay analysis.
                        </li>

                        <li>
                            Prepared samples through crushing, grinding,
                            digestion, and mineralization.
                        </li>

                        <li>
                            Prepared reagents, working, standard, and
                            calibration solutions.
                        </li>

                        <li>
                            Calibrated laboratory equipment.
                        </li>

                        <li>
                            Performed internal quality control and verified
                            analytical results.
                        </li>

                        <li>
                            Maintained laboratory documentation and
                            analytical records.
                        </li>

                    </ul>

                </section>


                <!-- EQUIPMENT -->

                <section class="card">

                    <h2>Methods & Equipment</h2>

                    <div class="tags">

                        <span class="tag">AAS</span>

                        <span class="tag">ICP-OES</span>

                        <span class="tag">XRF</span>

                        <span class="tag">Agilent 5100</span>

                        <span class="tag">
                            Thermo Scientific iCAP PRO
                        </span>

                        <span class="tag">
                            Epsilon 3XL
                        </span>

                        <span class="tag">
                            RLP-21
                        </span>

                        <span class="tag">
                            LECO
                        </span>

                        <span class="tag">
                            Spectroscan
                        </span>

                    </div>

                </section>

            </main>


            <aside>

                <!-- SKILLS -->

                <section class="card">

                    <h2>Key Skills</h2>

                    <ul>

                        <li>Chemical analysis</li>

                        <li>Instrumental analysis</li>

                        <li>Sample preparation</li>

                        <li>Solution preparation</li>

                        <li>Gravimetric analysis</li>

                        <li>Titrimetric analysis</li>

                        <li>Fire assay</li>

                        <li>Equipment calibration</li>

                        <li>Quality control</li>

                        <li>Laboratory documentation</li>

                        <li>
                            GOST, ISO, TU and internal procedures
                        </li>

                        <li>
                            Industrial safety and occupational health
                        </li>

                    </ul>

                </section>


                <!-- EDUCATION -->

                <section class="card">

                    <h2>Education</h2>

                    <h3>
                        M.Kh. Dulaty Taraz Regional University
                    </h3>

                    <p>
                        Bachelor's Degree
                    </p>

                    <p>
                        Chemical Engineering and Processes
                    </p>

                </section>


                <!-- ADDITIONAL -->

                <section class="card">

                    <h2>Additional</h2>

                    <ul>

                        <li>
                            Experience working with laboratory and
                            production departments.
                        </li>

                        <li>
                            Training and mentoring new laboratory employees.
                        </li>

                        <li>
                            Practical knowledge transfer to new employees.
                        </li>

                    </ul>

                </section>

            </aside>

        </div>

    </div>


    <footer>
        © 2026 Әділер Ақбергенов · Professional Resume
    </footer>

</div>


<script>

function changeLanguage(language) {

    document
        .querySelectorAll(".language-content")
        .forEach(function(element) {
            element.classList.remove("active");
        });

    document
        .getElementById(language)
        .classList.add("active");

    document.documentElement.lang = language;

}

</script>

</body>
</html>
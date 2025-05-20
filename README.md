<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Premium EMI Calculator with Advanced Analytics | Visual Loan Breakdown | Amortization Schedule | Financial Planning Tool">
    <meta name="keywords" content="EMI calculator, loan calculator, financial planner, debt management, loan analyzer">
    <meta name="author" content="Finance Master">
    <title>Ultimate EMI Calculator with Visual Analytics | Finance Master</title>
    <link rel="canonical" href="https://www.yourdomain.com/emi-calculator">
    
    <!-- Google AdSense -->
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
    
    <style>
        :root {
            --primary: #4361ee;
            --secondary: #3f37c9;
            --accent: #4895ef;
            --success: #4cc9f0;
            --danger: #f72585;
            --light: #f8f9fa;
            --dark: #212529;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', system-ui, sans-serif;
        }

        body {
            line-height: 1.6;
            color: var(--dark);
            background: linear-gradient(135deg, #f1f3f5 0%, #e9ecef 100%);
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 2rem;
        }

        .calculator-wrapper {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2rem;
            margin: 2rem 0;
        }

        .calculator-card {
            background: white;
            padding: 2rem;
            border-radius: 1.5rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .calculator-card:hover {
            transform: translateY(-5px);
        }

        .input-group {
            margin-bottom: 1.5rem;
        }

        .input-label {
            display: block;
            margin-bottom: 0.8rem;
            font-weight: 600;
            color: var(--dark);
            font-size: 1.1rem;
        }

        .input-field {
            width: 100%;
            padding: 1rem;
            border: 2px solid #dee2e6;
            border-radius: 0.75rem;
            font-size: 1.1rem;
            transition: border-color 0.3s ease;
        }

        .input-field:focus {
            border-color: var(--primary);
            outline: none;
        }

        .range-slider {
            width: 100%;
            margin: 1rem 0;
        }

        .calculate-btn {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            border: none;
            padding: 1rem 2rem;
            border-radius: 0.75rem;
            cursor: pointer;
            font-size: 1.1rem;
            width: 100%;
            transition: transform 0.2s ease;
        }

        .calculate-btn:hover {
            transform: scale(1.02);
        }

        .result-card {
            background: white;
            padding: 2rem;
            border-radius: 1.5rem;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            margin-top: 2rem;
            animation: fadeIn 0.5s ease;
        }

        .result-heading {
            color: var(--primary);
            margin-bottom: 1.5rem;
            font-size: 1.5rem;
        }

        .visualization-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }

        .chart-card {
            background: white;
            padding: 1.5rem;
            border-radius: 1rem;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }

        .pie-chart {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            margin: 0 auto;
            background: conic-gradient(
                var(--success) 0% var(--principal-percent),
                var(--danger) var(--principal-percent) 100%
            );
            transition: all 0.5s ease;
        }

        .summary-cards {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 1.5rem;
            margin: 2rem 0;
        }

        .summary-card {
            background: white;
            padding: 1.5rem;
            border-radius: 1rem;
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }

        .ad-section {
            margin: 3rem 0;
            text-align: center;
            background: white;
            padding: 1.5rem;
            border-radius: 1rem;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @media (max-width: 768px) {
            .calculator-wrapper {
                grid-template-columns: 1fr;
            }
            
            .summary-cards {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header Ad -->
        <div class="ad-section">
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
                 data-ad-slot="1234567890"
                 data-ad-format="auto"
                 data-full-width-responsive="true"></ins>
            <script>
                 (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>

        <header class="header">
            <h1 style="color: var(--primary); margin-bottom: 1rem;">Ultimate EMI Calculator</h1>
            <p style="font-size: 1.2rem; color: var(--dark);">Smart Financial Planning with Advanced Analytics</p>
        </header>

        <div class="calculator-wrapper">
            <div class="calculator-card">
                <div class="input-group">
                    <label class="input-label">Loan Amount (₹)</label>
                    <input type="number" id="loanAmount" class="input-field" placeholder="1,00,000">
                    <input type="range" class="range-slider" min="10000" max="10000000" step="10000">
                </div>

                <div class="input-group">
                    <label class="input-label">Interest Rate (%)</label>
                    <input type="number" id="interestRate" class="input-field" placeholder="8.5" step="0.1">
                    <input type="range" class="range-slider" min="1" max="30" step="0.1">
                </div>

                <div class="input-group">
                    <label class="input-label">Loan Tenure (Years)</label>
                    <input type="number" id="loanTenure" class="input-field" placeholder="5">
                    <input type="range" class="range-slider" min="1" max="30" step="1">
                </div>

                <button class="calculate-btn" onclick="calculateEMI()">Calculate Now</button>
            </div>

            <!-- Live Preview Card -->
            <div class="calculator-card">
                <h3 style="margin-bottom: 1.5rem; color: var(--primary);">Live Preview</h3>
                <div class="summary-cards">
                    <div class="summary-card">
                        <div style="color: var(--success); font-size: 1.5rem;">₹<span id="previewEMI">0</span></div>
                        <p>Monthly EMI</p>
                    </div>
                    <div class="summary-card">
                        <div style="color: var(--danger); font-size: 1.5rem;">₹<span id="previewInterest">0</span></div>
                        <p>Total Interest</p>
                    </div>
                    <div class="summary-card">
                        <div style="color: var(--primary); font-size: 1.5rem;">₹<span id="previewTotal">0</span></div>
                        <p>Total Payment</p>
                    </div>
                </div>
                
                <div class="chart-card">
                    <h4>Payment Distribution</h4>
                    <div class="pie-chart" style="--principal-percent: 50%"></div>
                </div>
            </div>
        </div>

        <!-- Results Section -->
        <div class="result-card" id="result">
            <h2 class="result-heading">Detailed Payment Breakdown</h2>
            
            <div class="visualization-grid">
                <div class="chart-card">
                    <h4>Amortization Schedule</h4>
                    <div class="amortization-table">
                        <table>
                            <thead>
                                <tr>
                                    <th>Year</th>
                                    <th>Principal</th>
                                    <th>Interest</th>
                                    <th>Balance</th>
                                </tr>
                            </thead>
                            <tbody id="yearlyBody">
                            </tbody>
                        </table>
                    </div>
                </div>

                <div class="chart-card">
                    <h4>Payment Timeline</h4>
                    <canvas id="timelineChart"></canvas>
                </div>
            </div>
        </div>

        <!-- Mid Content Ad -->
        <div class="ad-section">
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-format="fluid"
                 data-ad-layout-key="-gw-3+1f-3d+2z"
                 data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
                 data-ad-slot="0987654321"></ins>
            <script>
                 (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>

        <!-- Feedback Section -->
        <div class="calculator-card" style="margin-top: 2rem;">
            <h3 style="color: var(--primary); margin-bottom: 1.5rem;">Share Your Feedback</h3>
            <form id="feedbackForm">
                <textarea class="input-field" placeholder="Your valuable feedback helps us improve..." style="height: 120px;"></textarea>
                <button class="calculate-btn" type="submit" style="margin-top: 1rem;">Submit Feedback</button>
            </form>
        </div>
    </div>

    <script>
        // Enhanced EMI Calculation with Yearly Breakdown
        function calculateEMI() {
            const loanAmount = parseFloat(document.getElementById('loanAmount').value);
            const annualInterest = parseFloat(document.getElementById('interestRate').value);
            const years = parseFloat(document.getElementById('loanTenure').value);

            const monthlyInterest = annualInterest / 1200;
            const months = years * 12;
            
            const emi = (loanAmount * monthlyInterest * Math.pow(1 + monthlyInterest, months)) / 
                       (Math.pow(1 + monthlyInterest, months) - 1);
            
            let balance = loanAmount;
            let totalInterest = 0;
            let yearlyData = [];
            let yearlyPrincipal = 0;
            let yearlyInterest = 0;

            for(let month = 1; month <= months; month++) {
                const interest = balance * monthlyInterest;
                const principal = emi - interest;
                totalInterest += interest;
                balance -= principal;

                yearlyPrincipal += principal;
                yearlyInterest += interest;

                if(month % 12 === 0) {
                    yearlyData.push({
                        year: month / 12,
                        principal: yearlyPrincipal,
                        interest: yearlyInterest,
                        balance: Math.abs(balance)
                    });
                    yearlyPrincipal = 0;
                    yearlyInterest = 0;
                }
            }

            // Update Results
            document.getElementById('previewEMI').textContent = emi.toFixed(2);
            document.getElementById('previewInterest').textContent = totalInterest.toFixed(2);
            document.getElementById('previewTotal').textContent = (loanAmount + totalInterest).toFixed(2);

            // Update Yearly Table
            const yearlyBody = document.getElementById('yearlyBody');
            yearlyBody.innerHTML = yearlyData.map(item => `
                <tr>
                    <td>${item.year}</td>
                    <td style="color: var(--success);">₹${item.principal.toFixed(2)}</td>
                    <td style="color: var(--danger);">₹${item.interest.toFixed(2)}</td>
                    <td>₹${item.balance.toFixed(2)}</td>
                </tr>
            `).join('');

            document.getElementById('result').style.display = 'block';
        }

        // Initialize Range Sliders
        document.querySelectorAll('.range-slider').forEach(slider => {
            slider.addEventListener('input', function() {
                const inputField = this.previousElementSibling;
                inputField.value = this.value;
                calculateEMI();
            });
        });

        // Feedback Form Handling
        document.getElementById('feedbackForm').addEventListener('submit', function(e) {
            e.preventDefault();
            Swal.fire({
                icon: 'success',
                title: 'Feedback Submitted!',
                text: 'Thank you for helping us improve!'
            });
            this.reset();
        });
    </script>

    <!-- Structured Data -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "WebApplication",
        "name": "Ultimate EMI Calculator",
        "description": "Professional-grade loan calculator with detailed analytics and visual reporting",
        "applicationCategory": "FinancialApplication",
        "operatingSystem": "All",
        "offers": {
            "@type": "Offer",
            "price": "0",
            "priceCurrency": "USD"
        }
    }
    </script>
</body>
</html>

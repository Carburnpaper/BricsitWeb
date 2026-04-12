<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BRICS IT Pricing Tool</title>
    <style>
        :root {
            --navy: #001f3f;
            --silver: #C0C0C0;
            --orange: #FF8C00;
        }
        body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
            background: var(--navy); 
            color: white; 
            display: flex;
            justify-content: center;
            padding: 20px;
        }
        .container { width: 100%; max-width: 400px; text-align: center; }
        .card { 
            background: white; 
            color: #333; 
            padding: 25px; 
            border-radius: 15px; 
            border-top: 8px solid var(--orange);
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
        }
        h2 { color: var(--navy); margin-bottom: 5px; }
        p { color: #666; margin-bottom: 20px; font-size: 0.9em; }
        label { display: block; text-align: left; font-weight: bold; margin-top: 10px; font-size: 0.8em; color: var(--navy); }
        input, select { 
            width: 100%; padding: 12px; margin: 5px 0 15px 0; 
            border-radius: 8px; border: 1px solid #ddd; box-sizing: border-box; 
        }
        .calc-btn { 
            width: 100%; padding: 15px; background: var(--navy); 
            color: white; border: none; font-weight: bold; border-radius: 8px; cursor: pointer;
        }
        .result-box { 
            margin-top: 20px; padding: 15px; background: #f9f9f9; 
            border-radius: 8px; display: none; 
        }
        .price-text { font-size: 1.5em; color: var(--orange); font-weight: bold; }
        .wa-btn { 
            display: inline-block; margin-top: 15px; width: 100%; padding: 15px; 
            background: #25D366; color: white; text-decoration: none; 
            font-weight: bold; border-radius: 8px; box-sizing: border-box;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="card">
            <h2>BRICS IT BRAND EMPORIUM</h2>
            <p>Smart Pricing for Smart Branding</p>
            
            <label>Width (Inches)</label>
            <input type="number" id="w" placeholder="e.g. 2.5">
            
            <label>Height (Inches)</label>
            <input type="number" id="h" placeholder="e.g. 4">
            
            <label>Quantity</label>
            <input type="number" id="qty" placeholder="e.g. 150">
            
            <label>Job Type</label>
            <select id="process">
                <option value="engrave">Engrave Only</option>
                <option value="cut">Cut + Engrave</option>
            </select>
            
            <button class="calc-btn" onclick="calculate()">GET INSTANT QUOTE</button>
            
            <div id="resultBox" class="result-box">
                <div class="price-text" id="displayPrice"></div>
                <p id="totalOrder"></p>
                <a href="#" id="waLink" class="wa-btn" target="_blank">ORDER VIA WHATSAPP</a>
            </div>
        </div>
    </div>

    <script>
        function calculate() {
            // Get Values
            let w = parseFloat(document.getElementById('w').value);
            let h = parseFloat(document.getElementById('h').value);
            let qty = parseInt(document.getElementById('qty').value);
            let process = document.getElementById('process').value;
            
            if(!w || !h || !qty) { alert("Please fill all fields"); return; }

            // Math Logic
            let area = w * h;
            let material = (area / 156) * 2500;
            let laser = (1000/18) + (process === 'cut' ? 50 : 0);
            let labor = 150; // Base labor/finishing
            
            let unitCost = material + laser + labor;
            let markup = qty >= 100 ? 1.7 : (qty >= 50 ? 2.2 : 3.0);
            
            let unitPrice = Math.ceil((unitCost * markup) / 50) * 50;
            let totalOrder = unitPrice * qty;

            // Update UI
            document.getElementById('displayPrice').innerText = "₦" + unitPrice.toLocaleString() + " / unit";
            document.getElementById('totalOrder').innerText = "Total for " + qty + " pcs: ₦" + totalOrder.toLocaleString();
            document.getElementById('resultBox').style.display = "block";

            // WhatsApp Integration
            let myPhone = "2348035847685"; // REPLACE WITH YOUR PHONE NUMBER (e.g. 234803...)
            let msg = "Hello BRICS IT! I'd like to place an order:%0A" + 
                      "- Item: " + w + "x" + h + " inches%0A" +
                      "- Quantity: " + qty + "%0A" +
                      "- Process: " + (process === 'cut' ? 'Cut + Engrave' : 'Engrave Only') + "%0A" +
                      "- Estimated Quote: N" + totalOrder.toLocaleString();
            
            document.getElementById('waLink').href = "https://wa.me/" + myPhone + "?text=" + msg;
        }
    </script>
</body>
</html>

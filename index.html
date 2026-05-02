

<!DOCTYPE html>
<html>
<head>
    <title>Expense Logger</title>
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=0">
    <style>
        body { font-family: -apple-system, system-ui, sans-serif; background-color: #fcf6f7; display: flex; justify-content: center; padding: 15px; }
        .card { background: white; padding: 25px; border-radius: 15px; box-shadow: 0 10px 25px rgba(0,0,0,0.05); width: 100%; max-width: 450px; }
        h2 { color: #1a1a1a; margin-bottom: 20px; text-align: center; font-weight: 600; }
        .field { margin-bottom: 15px; }
        label { display: block; margin-bottom: 8px; font-weight: 500; color: #444; font-size: 14px; }
        input, select { width: 100%; padding: 12px; border: 1px solid #eee; border-radius: 10px; box-sizing: border-box; font-size: 16px; background-color: #fff; -webkit-appearance: none; }
        
        /* Updated to Soft Pink */
        button { width: 100%; padding: 15px; background-color: #f8bbd0; color: #5d4037; border: none; border-radius: 10px; cursor: pointer; font-size: 17px; font-weight: 600; margin-top: 10px; transition: background 0.3s; }
        button:active { background-color: #f48fb1; }
        button:hover { background-color: #f48fb1; }
        
        #status { margin-top: 20px; text-align: center; font-weight: 500; font-size: 15px; min-height: 20px; }
    </style>
</head>
<body>

<div class="card">
    <h2>Expense Logger</h2>
    <form id="expenseForm">
        <div class="field">
            <label>Date</label>
            <input type="date" id="date" name="Date" required>
        </div>
        
        <div class="field">
            <label>Category</label>
            <select name="Category" required>
                <option value="">Select Category</option>
                <option value="Swiggy/Blinkit">Swiggy/Blinkit</option>
                <option value="Amazon">Amazon</option>
                <option value="Lifestyle">Lifestyle</option>
                <option value="Other">Other</option>
                <option value="Utility Bills">Utility Bills</option>
                <option value="Home Expenses">Home Expenses</option>
                <option value="Fuel">Fuel</option>
                <option value="Jayesh">Jayesh</option>
            </select>
        </div>

        <div class="field">
            <label>Payment Mode</label>
            <select name="Mode" required>
                <option value="Card">Card</option>
                <option value="Cash">Cash</option>
                <option value="UPI">UPI</option>
            </select>
        </div>

        <div class="field">
            <label>Amount (₹)</label>
            <input type="number" name="Amount" placeholder="0.00" step="0.01" required>
        </div>

        <div class="field">
            <label>Description</label>
            <input type="text" name="Description" placeholder="Notes...">
        </div>

        <button type="submit" id="submitBtn">Log Expense</button>
    </form>
    <div id="status"></div>
</div>

<script>
    // PASTE YOUR NEW DEPLOYMENT URL HERE
const scriptURL = 'https://script.google.com/macros/s/AKfycbw50zoqskDiql4zmXbxmXc2Odj9iIgQAV10IgN3Vex-0paBkuOEyChpyukzny_oOIJ5/exec';
    
    const form = document.getElementById('expenseForm');
    const status = document.getElementById('status');

    form.addEventListener('submit', e => {
        e.preventDefault();
        status.innerHTML = "Logging to Google Sheets...";
        status.style.color = "#666";
        
        fetch(scriptURL, { 
    method: 'POST', 
    body: new FormData(form),
    mode: 'no-cors' // This specifically bypasses the "unique origin" security check
})
.then(() => {
    status.innerHTML = "✅ Entry Saved Successfully!";
    status.style.color = "#e91e63"; 
    form.reset();
    document.getElementById('date').valueAsDate = new Date();
})
            .catch(error => {
                status.innerHTML = "❌ Error: Check Connection";
                status.style.color = "#dc3545";
            });
    });

    document.getElementById('date').valueAsDate = new Date();
</script>

</body>
</html>

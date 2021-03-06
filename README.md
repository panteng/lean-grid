# lean-grid

A simple CSS layout framework based on CSS flexbox.

![Demo](https://raw.githubusercontent.com/panteng/lean-grid/master/demo.png)

All major browsers and IE 10+ supported.
For IE 9 support, please use [Flexibility](https://github.com/10up/flexibility) together with lean-grid.

## Usage

Install via npm:

    npm install lean-grid

If you know how to use Bootstrap Grid System, you know how to use lean-grid.

    <div class="grid">
        <div class="grid-row">
            <div class="grid-col-12"></div>
            <div class="grid-col-12"></div>
        </div>
        
        <div class=grid-row">
            <div class="grid-col-8"></div>
            <div class="grid-col-8 grid-col-offset-8"></div>
        </div>
    </div>
    
Unlike Bootstrap's 12 columns grid system, lean-grid divides a row into 24 columns.

## License

MIT

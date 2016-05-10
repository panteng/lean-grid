# Lean-Grid

A dead simple css grid system for dashboard webapps. No bullshit.

![Demo](https://raw.githubusercontent.com/panteng/lean-grid/master/demo.jpg)

IE 10+ supported. For IE 9 support, please use [Flexibility](https://github.com/10up/flexibility) with Lean-Grid.

## Usage

Install via NPM:

    npm install lean-grid

If you know how to use Bootstrap Grid System, you know how to use Lean-Grid.

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
    
Unlike Bootstrap's 12 columns grid system, Lean-Grid divides a row into 24 columns, which is more flexiable for dashboard webapps.

## License

MIT
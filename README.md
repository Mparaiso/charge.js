Charge.js
=========

A client-side javascript resource loader
----------------------------------------

### Usage

    Charge.load(['script.js','data.json'],
        function loaded(resources){
             console.log("loaded!",resources);
        }
    );

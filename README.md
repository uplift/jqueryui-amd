# jQuery UI AMD

## Usage

In your requirejs paths config add

    require({
        paths: {
            "jquery"  : "path/to/jquery",
            "jqueryui": "path/to/jqueryui/1.8.17"
        },
       //code
    })

In your define call add

    define(
        [
            'jqueryui/[widget]',
            'jqueryui/effects/[effect]
        ]
    )
    
## Licenses

jQueryUI has its own license, see jQueryUI project [repo](https://github.com/jquery/jquery-ui)
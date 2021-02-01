<!doctype html>
<script>

    class Clock {
        blockTime = 1
        constructor({ template }) {
            this.template = template
        }

        render() {
            this.blockTime > 5 ? this.stop() : null
            this.blockTime++
            let date = new Date();

            let hours = date.getHours();
            if (hours < 10) hours = '0' + hours;

            let mins = date.getMinutes();
            if (mins < 10) mins = '0' + mins;

            let secs = date.getSeconds();
            if (secs < 10) secs = '0' + secs;

            let output = this.template
                .replace('h', hours)
                .replace('m', mins)
                .replace('s', secs);

            console.log(output);
        }

        stop() {
            clearInterval(this.timer);
        };

        start() {
            this.render();
            this.timer = setInterval(() => this.render(), 1000);

        };

    }

    class ExtendedClock extends Clock {
        constructor(options) {
            super(options)
            let { precition = 2000 } = options
            this.precision = precition
        }

        start() {
            
                this.render()
                this.timer = setInterval(() => this.render(), this.precision)
            
        }


    }


    //   let clock = new Clock( {template:'h:m:s'});
    //   clock.start();
    let clock = new ExtendedClock({ template: 'h:m:s' });
    clock.start();

</script>

</html>
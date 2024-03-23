class UberPriceCalculator {

    Defaultfare = 2.0;
    
    PER_MILE_RATE = 1.5;

    PER_MINUTE_RATE = 0.5;
    
    constructor(distance, duration) {
    
    this.distance = distance;
    
    this.duration = duration;
    
    }
    
    calculateFare() {
    
    const distanceFare = this.distance * UberPriceCalculator.PER_MILE_RATE;
    
    const timeFare = this.duration * UberPriceCalculator.PER_MINUTE_RATE;
    
    const totalFare = UberPriceCalculator.Defaultfare + distanceFare + timeFare;
    
    return totalFare;
    
    }
    
    getDistance() {
    
    return this.distance;
    
    }
    
    setDistance(distance) {
    
    this.distance = distance;
    
    }
    
    getDuration() {
    
    return this.duration;
    
    }
    
    setDuration(duration) {
    
    this.duration = duration;
    
    }
    
    toString() {
    
    return UberPriceCalculator[distance=${this.distance.toFixed(2)} miles, duration=${this.duration} minutes];
    
    }
    
    }
    
    const calculator = new UberPriceCalculator(5.5, 15);
    
    console.log(calculator.toString());
    
    const fare = calculator.calculateFare();
    
    console.log("Total Fare:" ${fare.toFixed(2)});

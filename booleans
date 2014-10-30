module.exports.equalStrings = function(stringOne, stringTwo) {
  return stringOne == stringTwo;
};

module.exports.notEqual = function(one, two) {
  return one !== two;
};

module.exports.inBetween = function(lower, middle, upper) {
  return (lower < middle) && (middle < upper);
};

module.exports.outsideRanges = function(number) {
  //var between1020 = (10 < number) && (number < 20);
  var notBetween1020 = (number < 10) || (20 < number);
  var notBetween4275 = (number <= 42) || (75 < number);
  var notBetween16 = (number <= 1) || (6 <= number);
  return (notBetween1020 && notBetween4275 && notBetween16);
  // alternative way
  //return ( (number < 10) || (20 < number) ) && 
  //       ( (number < 42) || (75 < number) ) && 
  //       ( (number < 1) || (6 < number) );
};

module.exports.nameAndPrice = function(name, price) {
  var nameMatch = (name == 'NYTimes' || name == 'LATimes');
  var priceMatch = (price >= 1);
  return nameMatch && priceMatch;
};

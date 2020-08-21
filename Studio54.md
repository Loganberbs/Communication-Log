// Paste your makeLine function here:
function makeLine(size){
  let line = '';
  for(let i = 0; i < size; i++){
    line += '#';
    }
    return line;
}
// Code your makeDownwardStairs function here:
function makeDownwardStairs(height){
  let step = '#'; 
  for(let i = 0; i <= height; i++){
    step += (makeLine(i) +'\n');
  }
  return step.slice(0, -1);
}
console.log(makeDownwardStairs(5));
// Code your makeSpaceLine function here:
  
  function makeSpaceLine(height){
  let step = '#'; 
  for(let i = 0; i <= height; i++){
    step = (makeLine(i) +'\n');
  }
  return step.slice(0, -1);
}
console.log(makeSpaceLine(5));

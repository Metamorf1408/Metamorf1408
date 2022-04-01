    function Block(latter, beatle, used, mom, code) {
        this.latter = latter;
        this.rate = beatle;
        this.used = used;
        this.mom = mom;
        this.code = code;
}

function FindCode(Block) {

if (tree[block.mom].code !='') {
  block.code = tree[block.mom].code + '1';
}
  else {
  if (block.latter == tree[minIndex].latter) {
    block.code = '0';
  }
       else if (block.latter == tree[preminIndex].latter) {
    block.code = '1';
  }
       else {
       FindCode(tree[block.mom]);
       block.code = tree[block.mom].code + '0';
  }
 }
}

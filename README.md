# awk
### 01 分割符取第二部分：
    awk -F"the_separator" '{print $2}'
  
### 02 第一列的和：
    cat file | awk '{sum1+= $1}END{print sum1}'
### 03 第一列和第二列的平均值：
    cat test.txt | awk '{sum1+=$1;sum2+=$2;count++}END{print sum1/count,sum2/count}'

  

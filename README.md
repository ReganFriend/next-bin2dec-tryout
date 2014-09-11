next-bin2dec-tryout
===================
def bin2dec():
  num="10101"
  result=0
  for index in range(len(num)):
    digit=num[index]
    if digit=='1':
      result=result+pow(2,len(num)-1-index)
  return result

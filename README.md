# Simplex-programming-LPP
This a python program for solving Minimisation using (Big-M method)simplex programming LP.

  #m = gen_matrix(variables,constraints)
 EXAMPLE
 m = gen_matrix(4,2)
  constrain(m,'5,10,-1,0,G,8')
  constrain(m,'1,1,0,1,G,1')
  obj(m,'2,1,0,0,0')
  print(minz(m))

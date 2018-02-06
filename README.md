# pydata
izpeljevanje seznamov: seznam_3 = [3*el for el in seznam_1]

In [1]:

  seznam1 = np.array([2, 3.5, 6)]
  
  seznam2 = np.array([-5, 16])
  
  a = 9
  
  np.hstack((seznam1, a, seznam2))

Out [1]:

  array([2, 3.5, 6, 9, -5, 16])

np.vstack((a, b)) -> dodajanje vrstic matriki

np.column_stack((a, b)) -> dodajanje stolpcev matriki

# Miscallenous
All kinds of sorts and practice exercises


Finding Duplicates in two arrays.

public List<Integer> findDuplicates(m,n)
 {
    m_pointer = 0;
    n_pointer = 0;
    List<Integer> l = new ArrayList<Integer>(); 
    while (m_pointer < m.length && n_pointer < n.length)       
          if(m[m_pointer] > n[n_pointer])
             n_pointer++
           else if(m[m_pointer] == n[n_pointer] 
             l.add(m[m_pointer]
             m_pointer++
             n_pointer++           
           else 
              m_pointer++
         
  }

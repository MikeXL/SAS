

  \* libref;  
  libname hdp hadoop server=unicorn;

  \* passthru;  
  proc sql;
      connect to hadoop (server=unicorn);


the above solution would work, but that is so 1997, bring data to the compute. the new way of doing it is to bring the compute to the data, and in-memory, therefore SAS LASR, well the most expensive one. Apache Spark is close to do that, but kinda wait their R implementation *SparkR*


LLAP 🖖

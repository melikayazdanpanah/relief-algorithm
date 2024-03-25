# relief-algorithm
this is a python project for Implementation Feature selection using Relief Algorithm.

Algorithm Structure:

1. set all weights W[A] := 0;
2. for i := 1 to m do begin
3. randomly select an instance Ri;
4. find nearest hit H and nearest miss M;
5. for A := 1 to a do
6. W[A] :=W[A]+diff(A,Ri,H)/m-diff(A,Ri,M)/m;
7. end;

#TOOLS:
pandas library
numpy library

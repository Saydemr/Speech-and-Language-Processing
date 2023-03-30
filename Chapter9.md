# Chapter 9 - RNNs and LSTMs

- **Page 190, Equation 9.7**:

    `i` used both as a word and as an index. Overloading is unnecessary and confusing.

    ![image](images/ch9-eq97.png)

- **Page 202, Explanation of Components of Encoder Decoder Networks**:

    Superscript is used to imply the end index of the sequence which is not consistent with the chapter and the book. For input sequence x<sub>1:n</sub> is used throughout the book. Here, x<sup>n</sup><sub>1</sub> is used. Same problem exists for the output sequence y<sub>1:m</sub>.

    ![image](images/ch9-encdec.png)


- **Page 204, Figure 9.18**:

    Output length is not dependent on input length. Index of the last y should be m instead of n.

    ![image](images/ch9-fig918.png)


- **Page 208, Figure 9.23**:

    y<sub>i</sub> is computed from h<sub>i-1</sub> and h<sub>i</sub> is computed using y<sub>i</sub> which is not consistent with the previous figures and formulas. 

    ![image](images/ch9-figure923.png)

    In Figure 9.22, y<sub>i</sub> is computed from h<sub>i</sub> and in Equation 9.35, h<sub>i</sub> is computed from y<sub>i-1</sub>.
    
    ![image](images/ch9-figure922.png)

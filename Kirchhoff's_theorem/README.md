# kirchhoff.py

### 行列木定理が成り立っているか確認するコード  

    $ python kirchhoff.py --dim_fn <total node>

`--dim_fn <total node>`の部分でノードの数を指定する  
指定しなければ5つのノードの場合で計算する  

実行例  

    $ python kirchhoff.py --dim_fn 5  


結果

    Adjacency matrix  
    [[ 0.  0.  1.  1.  1.]  
    [ 0.  0.  0.  1.  0.]  
    [ 1.  0.  0.  1.  0.]  
    [ 1.  1.  1.  0.  1.]  
    [ 1.  0.  0.  1.  0.]]  
    Laplacian matrix  
    [[ 3.  0. -1. -1. -1.]  
    [ 0.  1.  0. -1.  0.]  
    [-1.  0.  2. -1.  0.]  
    [-1. -1. -1.  4. -1.]  
    [-1.  0.  0. -1.  2.]]  
    cofactors  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
    8.0  
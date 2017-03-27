# SQL

Theta (θ) Join
Theta join combines tuples from different relations provided they satisfy the theta condition. The join condition is denoted by the symbol θ.
R1 θ R2

Theta join can use all kinds of comparison operators.


Equijoin
When Theta join uses only equality comparison operator, it is said to be equijoin. 
Natural Join (⋈)
Natural join does not use any comparison operator. It does not concatenate the way a Cartesian product does. We can perform a Natural Join only if there is at least one common attribute that exists between two relations. In addition, the attributes must have the same name and domain.
Natural join acts on those matching attributes where the values of attributes in both the relations are same.
Outer Joins
Theta Join, Equijoin, and Natural Join are called inner joins. An inner join includes only those tuples with matching attributes and the rest are discarded in the resulting relation. Therefore, we need to use outer joins to include all the tuples from the participating relations in the resulting relation. There are three kinds of outer joins − left outer join, right outer join, and full outer join.
Left Outer Join (R  S)
All the tuples from the Left relation, R, are included in the resulting relation. If there are tuples in R without any matching tuple in the Right relation S, then the S-attributes of the resulting relation are made NULL.
Right Outer Join: (R  S)
All the tuples from the Right relation, S, are included in the resulting relation. If there are tuples in S without any matching tuple in R, then the R-attributes of resulting relation are made NULL.

Full Outer Join: (R  S)
All the tuples from both participating relations are included in the resulting relation. If there are no matching tuples for both relations, their respective unmatched attributes are made NULL.

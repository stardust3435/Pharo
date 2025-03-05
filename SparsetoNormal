| matrix values rowIndices colIndices |
matrix := #( #( 0 0 3 0 ) #( 0 0 0 4 ) #( 0 0 0 0 ) #( 5 0 0 0 ) ).
values := OrderedCollection new.
rowIndices := OrderedCollection new.
colIndices := OrderedCollection new.

matrix withIndexDo: [ :row  :i |
    row withIndexDo: [ :value :j |
        value = 0 ifFalse: [
            values add: value.
            rowIndices add: i.
            colIndices add: j.
        ].
    ].
].

Transcript show: 'Values: ', (values printString); cr.
Transcript show: 'Row Indices: ', (rowIndices printString); cr.
Transcript show: 'Column Indices: ', (colIndices printString); cr.

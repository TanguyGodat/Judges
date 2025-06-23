# Report for relations: education_education

periods
1800-1824      85
1825-1849     118
1850-1874     201
1875-1899     380
1900-1924     551
1925-1949    1182
1950-1974     988
1975-1999      59
dtype: int64



## Values for 1800-1824

Number of relationships for this period 85

Number of nodes: 79
Number of edges: 85

Beware: more than one big component !

Number of nodes for first component: 2
Number of edges for first component: 1



## Values for 1825-1849

Number of relationships for this period 118

Number of nodes: 110
Number of edges: 118

Beware: more than one big component !

Number of nodes for first component: 15
Number of edges for first component: 18



## Values for 1850-1874

Number of relationships for this period 201

Number of nodes: 186
Number of edges: 201

Beware: more than one big component !

Number of nodes for first component: 100
Number of edges for first component: 148

[('university', 54), ('public university', 28), ('private university', 18)]

Spearman's rank correlation of eidenvector and betweenness: 0.4938259187677358

Eigenvector
                                     label           mainType membersNumber
13                      Leipzig University  public university            22
39          Humboldt-Universität zu Berlin         university            12
44                    University of Zurich         university             6
40                  University of Tübingen  public university            13
38                   Heidelberg University  public university            13
41  Ludwig-Maximilians-Universität München  public university             9
37                      University of Bern  public university             8
-----
Betweenness                                   label            mainType membersNumber
25                  Princeton University  private university            12
13                    Leipzig University   public university            22
18                University of Michigan          university            52
5   University of Virginia School of Law          university            15
23               Phillips Exeter Academy          university             9
52   Frederick William University Berlin          university             2
42               University of Göttingen   public university             9

Number of communitites: 7
Number of nodes per community: [32, 18, 17, 14, 8, 6, 5]



## Values for 1875-1899

Number of relationships for this period 380

Number of nodes: 293
Number of edges: 380

Beware: more than one big component !

Number of nodes for first component: 191
Number of edges for first component: 308

[('university', 123), ('public university', 38), ('private university', 30)]

Spearman's rank correlation of eidenvector and betweenness: 0.41544891564368397

Eigenvector
                                      label           mainType membersNumber
107  Ludwig-Maximilians-Universität München  public university            32
101                  University of Freiburg  public university             9
79                    Heidelberg University  public university            19
99                       University of Bonn  public university            18
104     Frederick William University Berlin         university             5
103                   University of Marburg  public university            10
109                  University of Würzburg  public university            12
-----
Betweenness                               label            mainType membersNumber
71               Columbia University  private university            24
20                Harvard University  private university            27
108   Humboldt-Universität zu Berlin          university            22
59   University of Wisconsin–Madison          university            16
15              University of Oxford   public university             7
64            University of Michigan          university            40
67             University of Chicago  private university            10

Number of communitites: 10
Number of nodes per community: [57, 30, 24, 19, 16, 14, 11, 10, 6, 4]

Communities: 


Community 0
Betweenness|    | label                           | mainType           |   membersNumber |
|---:|:--------------------------------|:-------------------|----------------:|
| 71 | Columbia University             | private university |              24 |
| 20 | Harvard University              | private university |              27 |
| 59 | University of Wisconsin–Madison | university         |              16 |
| 15 | University of Oxford            | public university  |               7 |
| 67 | University of Chicago           | private university |              10 |
-----
Eigenvector|    | label                           | mainType           |   membersNumber |
|---:|:--------------------------------|:-------------------|----------------:|
| 20 | Harvard University              | private university |              27 |
| 71 | Columbia University             | private university |              24 |
| 67 | University of Chicago           | private university |              10 |
| 59 | University of Wisconsin–Madison | university         |              16 |
| 21 | University of Florida           | public university  |               8 |

Community 1
Betweenness|     | label                             | mainType           |   membersNumber |
|----:|:----------------------------------|:-------------------|----------------:|
|  37 | Georgetown University             | private university |              12 |
| 171 | George Washington University      | private university |              14 |
|  38 | University of Oklahoma            | university         |               8 |
|  88 | University of the Philippines     | university         |               6 |
| 146 | University of Maryland, Baltimore | public university  |               6 |
-----
Eigenvector|     | label                                                         | mainType           |   membersNumber |
|----:|:--------------------------------------------------------------|:-------------------|----------------:|
| 171 | George Washington University                                  | private university |              14 |
|  73 | University of Alabama                                         | public university  |               5 |
|  76 | University of Chicago School of Social Service Administration | university         |               1 |
|  36 | Brigham Young University                                      | private university |               3 |
| 170 | Vanderbilt University                                         | private university |               9 |

Community 2
Betweenness|     | label                              | mainType           |   membersNumber |
|----:|:-----------------------------------|:-------------------|----------------:|
|  64 | University of Michigan             | university         |              40 |
|  25 | Valparaiso University              | private university |              13 |
| 125 | University of Utah                 | university         |               5 |
|   5 | University of California, Berkeley | university         |              11 |
| 159 | Ohio State University              | university         |               7 |
-----
Eigenvector|     | label                          | mainType           |   membersNumber |
|----:|:-------------------------------|:-------------------|----------------:|
|  64 | University of Michigan         | university         |              40 |
| 159 | Ohio State University          | university         |               7 |
|  25 | Valparaiso University          | private university |              13 |
|  24 | Indiana University Bloomington | university         |               2 |
| 160 | Cornell University             | private university |              13 |

Community 3
Betweenness|     | label                          | mainType          |   membersNumber |
|----:|:-------------------------------|:------------------|----------------:|
| 108 | Humboldt-Universität zu Berlin | university        |              22 |
|  48 | University of Tokyo            | university        |              32 |
|  46 | University of Paris            | university        |              11 |
| 144 | Sciences Po                    | public university |               3 |
| 111 | University of Copenhagen       | university        |               7 |
-----
Eigenvector|     | label                                          | mainType   |   membersNumber |
|----:|:-----------------------------------------------|:-----------|----------------:|
| 108 | Humboldt-Universität zu Berlin                 | university |              22 |
|  46 | University of Paris                            | university |              11 |
| 118 | National and Kapodistrian University of Athens | university |               8 |
| 111 | University of Copenhagen                       | university |               7 |
| 112 | Lund University                                | university |               3 |

Community 4
Betweenness|     | label                               | mainType          |   membersNumber |
|----:|:------------------------------------|:------------------|----------------:|
|   2 | University of Vienna                | university        |              37 |
|  79 | Heidelberg University               | public university |              19 |
| 103 | University of Marburg               | public university |              10 |
| 104 | Frederick William University Berlin | university        |               5 |
|  99 | University of Bonn                  | public university |              18 |
-----
Eigenvector|     | label                                  | mainType          |   membersNumber |
|----:|:---------------------------------------|:------------------|----------------:|
| 107 | Ludwig-Maximilians-Universität München | public university |              32 |
| 101 | University of Freiburg                 | public university |               9 |
|  79 | Heidelberg University                  | public university |              19 |
|  99 | University of Bonn                     | public university |              18 |
| 104 | Frederick William University Berlin    | university        |               5 |



## Values for 1900-1924

Number of relationships for this period 551

Number of nodes: 426
Number of edges: 551

Just one big component with 2 nodes

Number of nodes for first component: 2
Number of edges for first component: 1



## Values for 1925-1949

Number of relationships for this period 1182

Number of nodes: 698
Number of edges: 1182

Just one big component with 601 nodes

Number of nodes for first component: 601
Number of edges for first component: 1121

[('university', 406), ('public university', 140), ('private university', 55)]

Spearman's rank correlation of eidenvector and betweenness: 0.48862257546467636

Eigenvector
                                    label            mainType membersNumber
93   University of Virginia School of Law          university            94
22      New York University School of Law          university            52
21                    New York University  private university            34
97                   Princeton University  private university            40
211                    Fordham University  private university            17
54                        Yale University  private university            30
213                   Columbia University  private university            36
-----
Betweenness                                    label            mainType membersNumber
93   University of Virginia School of Law          university            94
213                   Columbia University  private university            36
5            George Washington University  private university            49
25                   University of Oxford   public university            20
20                     Harvard University  private university            69
106                  University of London          university            43
70                    University of Paris          university            18

Number of communitites: 15
Number of nodes per community: [135, 64, 61, 46, 43, 43, 39, 38, 37, 31, 23, 20, 8, 7, 6]

Communities: 


Community 0
Betweenness|    | label                                | mainType           |   membersNumber |
|---:|:-------------------------------------|:-------------------|----------------:|
| 93 | University of Virginia School of Law | university         |              94 |
| 22 | New York University School of Law    | university         |              52 |
| 54 | Yale University                      | private university |              30 |
|  8 | Stanford Law School                  | university         |              35 |
| 97 | Princeton University                 | private university |              40 |
-----
Eigenvector|     | label                                | mainType           |   membersNumber |
|----:|:-------------------------------------|:-------------------|----------------:|
|  93 | University of Virginia School of Law | university         |              94 |
|  22 | New York University School of Law    | university         |              52 |
|  21 | New York University                  | private university |              34 |
|  97 | Princeton University                 | private university |              40 |
| 211 | Fordham University                   | private university |              17 |

Community 1
Betweenness|     | label                            | mainType   |   membersNumber |
|----:|:---------------------------------|:-----------|----------------:|
| 106 | University of London             | university |              43 |
|  48 | University College London        | university |              22 |
| 399 | National University of Singapore | university |              10 |
| 159 | Free University of Brussels      | university |               5 |
| 393 | King's College London            | university |              15 |
-----
Eigenvector|     | label                         | mainType          |   membersNumber |
|----:|:------------------------------|:------------------|----------------:|
| 106 | University of London          | university        |              43 |
|  48 | University College London     | university        |              22 |
| 357 | Trinity College               | university        |              16 |
| 198 | University of the Punjab      | public university |              14 |
| 400 | University of the West Indies | public university |              10 |

Community 2
Betweenness|     | label                     | mainType           |   membersNumber |
|----:|:--------------------------|:-------------------|----------------:|
| 213 | Columbia University       | private university |              36 |
|  20 | Harvard University        | private university |              69 |
| 155 | Cornell University        | private university |              22 |
| 245 | Georgetown University     | private university |              27 |
| 241 | University of Puerto Rico | public university  |              16 |
-----
Eigenvector|     | label                     | mainType           |   membersNumber |
|----:|:--------------------------|:-------------------|----------------:|
| 213 | Columbia University       | private university |              36 |
| 155 | Cornell University        | private university |              22 |
| 241 | University of Puerto Rico | public university  |              16 |
| 239 | University of Notre Dame  | private university |              25 |
|  27 | University of Utah        | university         |              21 |

Community 3
Betweenness|     | label                                  | mainType          |   membersNumber |
|----:|:---------------------------------------|:------------------|----------------:|
|  70 | University of Paris                    | university        |              18 |
| 318 | Ludwig-Maximilians-Universität München | public university |              39 |
| 455 | Panthéon-Assas University Paris        | university        |               7 |
| 284 | University of Wisconsin–Madison        | university        |              16 |
| 324 | University of Bonn                     | public university |              21 |
-----
Eigenvector|     | label                           | mainType          |   membersNumber |
|----:|:--------------------------------|:------------------|----------------:|
| 284 | University of Wisconsin–Madison | university        |              16 |
|  70 | University of Paris             | university        |              18 |
| 352 | Leiden University               | university        |              34 |
| 203 | Middlebury College              | university        |               3 |
| 202 | Eastern Michigan University     | public university |               2 |

Community 4
Betweenness|     | label                                      | mainType          |   membersNumber |
|----:|:-------------------------------------------|:------------------|----------------:|
|  25 | University of Oxford                       | public university |              20 |
|  43 | University of Ottawa                       | public university |               9 |
| 104 | University of Toronto Faculty of Law       | university        |              10 |
| 257 | Magdalen College                           | university        |              14 |
|  72 | University of New Brunswick Faculty of Law | university        |               4 |
-----
Eigenvector|     | label                                      | mainType          |   membersNumber |
|----:|:-------------------------------------------|:------------------|----------------:|
|  25 | University of Oxford                       | public university |              20 |
| 257 | Magdalen College                           | university        |              14 |
|  72 | University of New Brunswick Faculty of Law | university        |               4 |
|  68 | University of New Brunswick                | university        |               6 |
|  71 | St John's College                          | university        |               2 |



## Values for 1950-1974

Number of relationships for this period 988

Number of nodes: 739
Number of edges: 988

Just one big component with 5 nodes

Number of nodes for first component: 5
Number of edges for first component: 4



## Values for 1975-1999

Number of relationships for this period 59

Number of nodes: 91
Number of edges: 59

Beware: more than one big component !

Number of nodes for first component: 2
Number of edges for first component: 1

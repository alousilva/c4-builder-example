# 2 Deployment

![diagram](https://www.plantuml.com/plantuml/svg/0/rLPBJnin4BuZyH-ckHGG96I5MjGJ8Q4jY92e6qehLKApjfEuzTehsnjAA_vxnzuyQP0QE7KFqNeotpo-cV7iYVDeVPchxQtNy4fgfaekOEnzuTur6XRlwYFfnsLMEc6PqLveNsScRo2t4lL4bKNPQ1yTz1LgVzszR3JhoM5oM6--9UbjHnJAtES1KqGNSmSAxqtftLgbxQtBrjVUzU3svdpmyVRoxCFPLMTdDyWNghTNXekTGh5zg9tA4PoY_W5qh3qw0qUFm0WXR6ttz_OMqFFO3DU4okGe8z015d9lR--R_taSR5rdfVObDD_K3u_WSf3ERQopWmMoiI1KAxx0mEGCVUsn08xhFrViXATDtABKmf8L6H3zSsWLXP84a4O78nSuGK3D8Isir2FeVcu7ST-QYUJ2mNb8KWiVamyAmrAp04Ob_JrC9A7X8krTDJuE1lqKo4Mzjhi8uw5wVLXFqfGVdXqsbzWAnurvCXQP2ZpruWiSGD_A7ErzRI5h9knfZZhP3iz8jqF5pT29WFia55R9mamCAP6UO_WtzSOIHQ6BmOgHTDv6RP1wQ6mUt_TXZ6uiE63fnnJib7fWLl1mHENs0HaJpe4o8pe8pvx5OBBAOF9C1fDb2bD1uyat9J7v_rZCbjcx4rarhKVFdDRafUDA4H3YHcJ_EAuTeUH4M0V43j3bImJ1z6ADsa7yroGx-g5w5ZWIW0itJz3siEwkp4s8irqwRt9XNpiWWIIRN4ma4rNM1PtFUoaO2otDhP5ydlWYuGf7-jtA0C42-WlI14kzSYCXA9bBJytWoinHFcQuFh_LcyeRODCuNRos22FjQi0nzRM9qdOgLZCDaZ8iW12qf3NcpD33ZTJStBaGKvLvZgoNFhaaCalAmavhVLgTWiKFneJQjCUMtEr3r_oIIY6ybrOCpMhdB4Xq1OPvgihQ3sLTqpqfixAekgAbHwL2kygkKYyZb5eNfcdDEsdMFdGHp2jTRQGk_Y2dOIynyapzQq8qtvtHrJu95W8gfhOP9CvGHSbYF4pCZ2tAk1Jk31ZTn5NmII1tCAGQHBxkBBNTpE55vxJz295i00dsPuYgHgGMloj8DtwNd0ZDwTFb3m00)

**Deployment diagram**

A deployment diagram allows you to illustrate how containers in the static model are mapped to infrastructure. This deployment diagram is based upon a UML deployment diagram, although simplified slightly to show the mapping between containers and deployment nodes. A deployment node is something like physical infrastructure (e.g. a physical server or device), virtualised infrastructure (e.g. IaaS, PaaS, a virtual machine), containerised infrastructure (e.g. a Docker container), an execution environment (e.g. a database server, Java EE web/application server, Microsoft IIS), etc. Deployment nodes can be nested.

**Scope**: A single software system.

**Primary elements**: Deployment nodes and containers within the software system in scope.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.
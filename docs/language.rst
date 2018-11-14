=======
Grammar
=======


Intro
=====



Grammar
=======

.. productionlist:: tospa
   QUERY : "?-" `EXPR` .
   EXPR : `RELATION` { "," `EXPR` }.
   RELATION : `identifier` "(" `identifier` { "," `identifier` } ")".
   identifier : "a" | ... | "z" | "A" | ... | "Z"

object -> classへの参照とインスタンス変数を持つ
class  -> superclassへの参照とmethodを持つ
String.instance_methods == 'hoge'.methods
Class.instance_methos == String.methods

Class.instance_methods == [:superclass, :new, ...]
-> 継承関係が作れて, インスタンス化できる！


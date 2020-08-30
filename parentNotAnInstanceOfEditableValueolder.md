Error: Parent not an instance of EditableValueHolder
Error Reason: some html component did not put into suitable place
e.g. 
<f:convertNumber minFractionDigits="1" />
outside of <h:inputText></h:inputText>

method: put the component into the suitable place


中文版

错误：Parent not an instance of EditableValueHolder
错误解释： 提示中的component组件没有放在合适的holder中
例子如上，验证组件放在了input组件的外边
解决方案： 调整顺序，放进去即可
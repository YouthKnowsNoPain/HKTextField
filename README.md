# HKTextField

public enum HKTextFieldType:Int {

​    case none // 不限制

​    case count // 数量 可以0在首位

​    case countNonZeroFront // 数量类 非0开头(可以单0)

​    case money // 金额类 默认小数点后保留2位

}



​    @IBInspectable var textMaxLength = 0 // // 最大长度

​    @IBInspectable var moneyMaxDecimal:Int = 2 // 小数点后保留2位
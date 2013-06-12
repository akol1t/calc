# -*- coding: UTF-8
# чуть позже выучу стайлд гайд
x = true
while (x == true) # цикл на необходимость выполнения новой операции калькулирования

y = true
while (y == true) # цикл проверки соответсвия введенных значений операндов
  puts 'Введите левый операнд'
  first = gets
if /\d/.match("#{first}") || /\./.match("#{first}") && /\S/.match("#{first}")
  y = false
  else p 'Введите числовые значения'
end
end

y = true
while (y == true)
  puts 'Введите знак операции "+","-","/","*"'
  operand = gets.chomp
if operand == "+" || "-" || "/" || "*"
  y = false
else 
  puts 'Введите знакэ' 
end  # warning string literal in condition wtf?
end

y = true
while (y == true)
  puts 'Введите правый операнд'
  second = gets
if /\d/.match("#{second}") || /\./.match("#{second}") && /\S/.match("#{second}")
  y = false
else p 'Введите числовые значения'
end
end

result = case operand 
  when "+"
  result = first.to_f + second.to_f
  when "-"
  result = first.to_f - second.to_f
  when "*"
  result = first.to_f * second.to_f
  when "/"
  begin
  result = first.to_f / second.to_f
  rescue ZeroDivisionError => e
end
end

  puts result

  puts 'Хотите выполнить еще одну операцию?'
  response = gets
case response 
     when /^[yY]/ 
     x = true
     when /^[Nn]/
     x = false
end
end

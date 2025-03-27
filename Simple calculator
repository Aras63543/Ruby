print 'Hello please write the first number: '
first_number = gets.chomp.to_i
print 'Please write the second number: '
second_number = gets.chomp.to_i
puts 'Choose the operation you want to do:'
puts '1 - Addition'
puts '2 - Subtraction'
puts '3 - Multiplication'
puts '4 - Division'
choice = gets.chomp.to_i

case choice
when 1
  puts "Result: #{first_number + second_number}"
when 2
  puts "Result: #{first_number - second_number}"
when 3
  puts "Result: #{first_number * second_number}"
when 4
  if second_number == 0
    puts 'Division by zero is not allowed'
    else 
    puts "Result: #{first_number / second_number}"
end
  else 
  puts 'Invalid choice'
end

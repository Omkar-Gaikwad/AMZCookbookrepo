cookbook_file "/tmp/bottle.py" do
  source "bottle.py"
  mode 0755
end

cookbook_file "/tmp/hello.py" do
  source "hello.py"
  mode 0755
end

cookbook_file "/tmp/runmyhello.sh" do
  source "runmyhello.sh"
  mode 0755
end


execute "runprog" do
  command "sh /tmp/runmyhello.sh"
end


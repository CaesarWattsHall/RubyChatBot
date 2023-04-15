require 'telegram_bot_api'

# Create a new bot instance
bot = TelegramBotAPI.new('YOUR_API_TOKEN')

# Define a method to handle incoming messages
def handle_message(message)
  # Print the message text to the console
  puts "Received message: #{message.text}"
  
  # Send a reply message
  bot.send_message(chat_id: message.chat.id, text: "You said: #{message.text}")
end

# Start listening for incoming messages
bot.listen(handle_message)

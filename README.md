const config = require("./config")
# TrapKingconst config = require("./config");

// Example owner command
if (text === ".owner") {
  await sock.sendMessage(from, {
    text: `👑 *Owner Information*

Name: ${config.ownerName}
Bot: ${config.botName}`
  });
}
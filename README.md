# draw-THEON


function drawTheon() {
  const asciiArt = [
    '  _______ _    _ ______  ____  _   _ ',
    ' |__   __| |  | |  ____|/ __ \\| \\ | |',
    '    | |  | |__| | |__  | |  | |  \\| |',
    '    | |  |  __  |  __| | |  | | . ` |',
    '    | |  | |  | | |____| |__| | |\\  |',
    '    |_|  |_|  |_|______|\\____/|_| \\_|',
  ].join('\n');
  if (typeof window !== 'undefined') {
    window.localStorage.setItem('author', asciiArt);
  }
}
drawTheon();


function drawTheon() {
  console.log("  _______ _    _ ______  ____  _   _ ");
  console.log(" |__   __| |  | |  ____|/ __ \\| \\ | |");
  console.log("    | |  | |__| | |__  | |  | |  \\| |");
  console.log("    | |  |  __  |  __| | |  | | . ` |");
  console.log("    | |  | |  | | |____| |__| | |\\  |");
  console.log("    |_|  |_|  |_|______|\\____/|_| \\_|");
}

// Gọi hàm để hiển thị
drawTheon();

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


Приложение из курса по андроид от Mail.ru 2019г.: https://polis-mail-ru.github.io/2019-android/01_intro/015_doom_fire/

 Заливка синим цветом
   // canvas.drawColor(Color.BLUE);


  Прямоугольники:
    //paint.setColor(Color.GREEN);
    //
    //	final int size = 300;
    //    for (int x = 0; x < width; x += size) {
    //        for (int y = 0; y < height; y += size) {
    //            paint.setColor(0x00ffffff & (1257823419 * x + 2118746214 * y) | 0xff000000);
    //            canvas.drawRect(x, y, x + size, y + size, paint);
    //        }
    //    }

  Круги
    //    int centerX = width / 2;
    //    int centerY = height / 2;
    //    int padding = 50;
    //    int minSide = Math.min(width, height);
    //    int contentSize = minSide - 2 * padding;
    //    int overlap = 300;
    //    int radius = (contentSize + overlap) / 4;
    //    int dist = 2 * radius - overlap;
    //
    //    float x1 = centerX - dist / 2;
    //    float x2 = centerX + dist / 2;
    //    float x3 = centerX;
    //
    //    float d = dist / 2 / (float) Math.sqrt(3f);
    //    float y1 = centerY + d;
    //    float y2 = y1;
    //    float y3 = centerY - 2 * d;
    //
    //    paint.setColor(Color.YELLOW & 0x7fffffff);
    //    canvas.drawCircle(x1, y1, radius, paint);
    //    paint.setColor(Color.MAGENTA & 0x7fffffff);
    //    canvas.drawCircle(x2, y2, radius, paint);
    //    paint.setColor(Color.BLUE & 0x7fffffff);
    //    canvas.drawCircle(x3, y3, radius, paint);

   Произвольные фигуры
    //    int centerX = width / 2;
    //    int centerY = height / 2;
    //    int padding = 50;
    //    int minSide = Math.min(width, height);
    //    int contentSize = minSide - 2 * padding;
    //
    //    float segmentSize = contentSize / 3;
    //
    //    Path path = new Path();
    //    path.moveTo(segmentSize, 0);
    //    path.lineTo(2 * segmentSize, 0);
    //    path.lineTo(2 * segmentSize, segmentSize);
    //    path.lineTo(3 * segmentSize, segmentSize);
    //    path.lineTo(3 * segmentSize, 3 * segmentSize);
    //    path.lineTo(2 * segmentSize, 3 * segmentSize);
    //    path.lineTo(2 * segmentSize, 2 * segmentSize);
    //    path.lineTo(segmentSize, 2 * segmentSize);
    //    path.lineTo(segmentSize, 3 * segmentSize);
    //    path.lineTo(0, 3 * segmentSize);
    //    path.lineTo(0, segmentSize);
    //    path.lineTo(segmentSize, segmentSize);
    //    path.lineTo(segmentSize, 0);
    //
    //    path.offset(centerX - 1.5f * segmentSize, centerY - 1.5f * segmentSize);
    //
    //    paint.setColor(Color.WHITE);
    //    paint.setStyle(Paint.Style.STROKE);
    //    paint.setStrokeCap(Paint.Cap.ROUND);
    //    paint.setStrokeJoin(Paint.Join.ROUND);
    //    paint.setStrokeWidth(20);
    //
    //    canvas.drawPath(path, paint);


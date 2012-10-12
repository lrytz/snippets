# Write String to File

    def write(s: String, f: String) {
      val out = new java.io.PrintWriter(new java.io.File(f))
      try { out.print(s) }
      finally { out.close() }
    }

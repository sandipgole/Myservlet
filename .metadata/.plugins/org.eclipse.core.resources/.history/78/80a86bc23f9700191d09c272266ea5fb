import java.io.IOException;
import java.io.PrintWriter;

import javax.servlet.http.HttpServlet;
import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;

public class CreateAccountServlet extends HttpServlet{
	public void doGet(HttpServletRequest req,HttpServletResponse res) throws IOException {
		res.setContentType("text/html");
		String fname = req.getParameter("fname");
		String lname=req.getParameter("lname");
		String email=req.getParameter("email");
		String adress=req.getParameter("address");
		String branch=req.getParameter("branch");
		String num= req.getParameter("number");
		String gender=req.getParameter("gender");
		PrintWriter out=res.getWriter();
		out.println("FirtsName:"+fname);
		out.println("<br>");
		out.println("LastName:"+lname);
		out.println("<br>");
		out.println("Email:"+email);
		out.println("<br>");
		out.println("Address:"+adress);
		out.println("<br>");
		out.println("Branch:"+branch);
		out.println("<br>");
		out.println("Phone_no:"+num);
		out.println("<br>");
		out.println("Gender:"+gender);
		out.println("<br>");
		
		
		
		
		

		}
	
	
	
	

}

package com.student.resource.controller;

import org.springframework.http.ResponseEntity;
import org.springframework.web.bind.annotation.PathVariable;
import org.springframework.web.bind.annotation.RequestMapping;

import com.student.model.StudentModel;

@RequestMapping(value="/api")
public interface IStudentResource {

	@RequestMapping(value="/students/id/{id}")
	public ResponseEntity<StudentModel> getById(@PathVariable int id);
	
	@RequestMapping(value="/students/name/{name}")
	public ResponseEntity<StudentModel> getByName(@PathVariable String name);
}
